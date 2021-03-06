# Button

It's a button. What more do you expect?

## Usage

Buttons express what action will occur when the user clicks or touches it. Buttons are used to initialize an action, either in the background or foreground of an experience.

```jsx
import { AksaraReset, Button } from '@aksara/ui-kit';

export default function MyApp({ children }) {
  return (
    <AksaraReset>
      <Button variant="primary" onClick={() => alert('Hello!')}>
        Push Me
      </Button>
    </AksaraReset>
  );
}
```

Button accepts all the HTML props available in a standard HTML `<button>` element. It has three supported sizes, `sm`, `md`, and `lg`.

```jsx
import { AksaraReset, Button } from '@aksara/ui-kit';

export default function MyApp({ children }) {
  return (
    <AksaraReset>
      <Button size="sm">Push Me</Button>
      <Button size="md">Push Me</Button>
      <Button size="lg">Push Me</Button>
    </AksaraReset>
  );
}
```

See more usage in the _JSX_ panel

## Props

| Property  | Type           | Required | Default   | Description                                     |
| --------- | -------------- | -------- | --------- | ----------------------------------------------- |
| className | string         | -        | undefined | Additional CSS classes to give to the component |
| style     | CSSProperties  | -        | undefined | Additional CSS styles to give to the component  |
| block     | boolean        | -        | false     | Is a block button.                              |
| variant   | ButtonVariants | -        | default   | The variant of the button.                      |
| size      | ButtonSizes    | -        | md        | The size of the button.                         |

See detailed props usage in the _Props_ panel
