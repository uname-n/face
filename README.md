# Face

<p align="center">
  <br />
  <img src="docs/example.png" alt="example" />
  <br /><br />
</p>

Animated SVG character faces as a web component. Drop in a single script and use `<face-rig>` anywhere.

## Usage

```html
<script src="https://cdn.jsdelivr.net/gh/uname-n/face@master/face.min.js"></script>
<face-rig state="targeting" style="color: black;" />
```

## States

| Static | Animated |
|--------|----------|
| `happy` | `idling` |
| `sad` | `searching` |
| `staring` | `targeting` |
| `pondering` | `entranced` |
| `cool` | `booting` |
| `possessed` | `konami` |
| `frustrated` |  |
| `demotivated` |  |
| `intense` |  |

## Attributes

| Attribute | Description |
|-----------|-------------|
| `state` | Face state name (defaults to `idling`) |
| `disable` | Disables animation and bounce |
| `style="color: ..."` | Sets the face color via CSS color inheritance |