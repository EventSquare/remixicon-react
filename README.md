# eventsquare-remixicon-react-builder

[Remix Icons](https://remixicon.com/) for React packaged as single components

This repo is based on the very good [mdi-react](https://github.com/levrik/mdi-react) package.

## Installation

```bash
npm install eventsquare-remixicon-react
# or if you use Yarn
yarn add eventsquare-remixicon-react
```

## Usage

Just search for an icon on [remixicon.com](https://remixicon.com) and look for its name.  
The name translates to Svg followed by the name in `remixicon-react` converted to PascalCaseIcon.

For example the icons named `alert-line` and `alert-fill`:

```javascript
import AlertLineIcon from 'eventsquare-remixicon-react/AlertLineIcon';
import AlertFillIcon from 'eventsquare-remixicon-react/AlertFillIcon';

const MyComponent = () => {
  return (
    <div>
      <AlertFillIcon />
      <AlertLineIcon className="some-class" />
    </div>
  );
};
```
