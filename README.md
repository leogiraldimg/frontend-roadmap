# frontend-roadmap

- [Reference link](https://roadmap.sh/frontend)

## Material UI

[Official site](https://mui.com/pt/)

### Installation

#### Material UI

```console
$ npm install @material-ui/core
```

#### Material UI - Icons

```console
$ npm install @material-ui/icons
```

### Button

[Documentation link](https://mui.com/material-ui/react-button/)

```javascript
import Button from "@material-ui/core/Button";
import SaveIcon from "@material-ui/icons/Save";

function App() {
  return (
    <Button
      startIcon={<SaveIcon />} // icon placed at the left position of the button text
      endIcon={<SaveIcon />} // icon placed at the right position of the button text
      onClick={() => alert("Hello")}
      variant="contained"
      color="primary"
      size="large"
      disabled
      style={{
        fontSize: 14,
      }}
    >
      Hello World
    </Button>
  );
}
```
