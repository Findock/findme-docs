# Storybook

Używamy storybook'a aby ułatwić proces tworzenia komponentów w naszej aplikacji.

## Jak uruchomić

Najpierw uruchamiamy serwer storybooka, z którym aplikacja w trybie storybook'a będzie się łączyła.

```bash
$> yarn storybook
```

Następnie serwujemy aplikację w trybie storybook'a.

```bash
$> yarn start:storybook
```

Na koniec łączymy się z serwowaną aplikacją przez expo. Oraz możemy tworzyć komponenty w storybook'u.

## Cheatsheet

### Typy knobs'ów

#### [Text](https://github.com/storybookjs/storybook/tree/master/addons/knobs#text)

```js
import { text } from '@storybook/addon-knobs';

<Component :text={text(label, defaultValue, ?groupId)} />
```

#### [Boolean](https://github.com/storybookjs/storybook/tree/master/addons/knobs#boolean)

```js
import { boolean } from '@storybook/addon-knobs';

<Component :boolean={boolean(label, defaultValue, ?groupId)} />
```

#### [Number](https://github.com/storybookjs/storybook/tree/master/addons/knobs#number)

```js
import { number } from '@storybook/addon-knobs';

<Component :number={number(label, defaultValue, ?options, ?groupId)} />
```

#### [Color](https://github.com/storybookjs/storybook/tree/master/addons/knobs#color)

```js
import { color } from '@storybook/addon-knobs';

<Component :color={color(label, defaultValue, ?groupId)} />
```

#### [Object](https://github.com/storybookjs/storybook/tree/master/addons/knobs#object)

```js
import { object } from '@storybook/addon-knobs';

<Component :object={object(label, defaultValue, ?groupId)} />
```

#### [Array](https://github.com/storybookjs/storybook/tree/master/addons/knobs#array)

```js
import { array } from '@storybook/addon-knobs';

<Component :array={array(label, defaultValue, ?separator, ?groupId)} />
```

#### [Select](https://github.com/storybookjs/storybook/tree/master/addons/knobs#select)

```js
import { select } from '@storybook/addon-knobs';

<Component :select={select(label, options, defaultValue, ?groupId)} />
```

#### [Radio buttons](https://github.com/storybookjs/storybook/tree/master/addons/knobs#radio-buttons)

```js
import { radios } from '@storybook/addon-knobs';

<Component :radios={radios(label, options, defaultValue, ?groupId)} />
```

#### [Options](https://github.com/storybookjs/storybook/tree/master/addons/knobs#options)

```js
import { optionsKnob } from '@storybook/addon-knobs';

<Component :optionsKnob={optionsKnob(label, valuesObj, defaultValue, ?optionsObj, ?groupId)} />
```

#### [Files](https://github.com/storybookjs/storybook/tree/master/addons/knobs#files)

```js
import { files } from '@storybook/addon-knobs';

<Component :files={files(label, accept, ?defaultValue, ?groupId)} />
```

#### [Date](https://github.com/storybookjs/storybook/tree/master/addons/knobs#date)

```js
import { date } from '@storybook/addon-knobs';

<Component :date={date(label, defaultValue, ?groupId)} />
```

### Przykładowe story
```js
import { storiesOf } from '@storybook/react-native';
import { text, select } from '@storybook/addon-knobs';
import ExampleComponent from '../../components/ExampleComponent';
import CenterView from './CenterView';

const colorOptions = [
  'red',
  'blue',
  'black'
]

storiesOf('ExampleComponent', module)
  .addDecorator((getStory) => <CenterView>{getStory()}</CenterView>)
  .add('ExampleComponent - ExampleText', () => (
    <ExampleComponent text={text('title', 'ExampleText')} color={select('color', colorOptions, 'blue')} />
  ))
  .add('ExampleComponent - ExampleText [RED]', () => (
    <ExampleComponent text={text('title', 'ExampleText')} color={select('color', colorOptions, 'red')} />
  ))

```
