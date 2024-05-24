# Example
You can read how the source code works in the [example.lua](./example.lua) file.

# Usage
```lua
exports.Lights:createLight(GetCurrentResourceName()) -- Resource Name
```
# Functions
| Function          | Description                                              | Argument Type                 | Example                              |
|-------------------|----------------------------------------------------------|-------------------------------|--------------------------------------|
| `setCoord()`      | Sets the coordinates to the specified 3D vector.          | vector3                      | `exports.Lights.setCoord(vector3(100,100,100))`       |
| `render()`        | Renders the current scene or object.                     | None                          | `exports.Lights.render()`                           |
| `onlyNight()`     | Sets whether to render only at night.                    | boolean                       | `exports.Lights.onlyNight(true)`                    |
| `setNight()`      | Sets the night duration or night mode settings.          | number                        | `exports.Lights.setNight(20)`                        |
| `setDay()`        | Sets the day duration or day mode settings.              | number                        | `exports.Lights.setDay(6)`                         |
| `setRenderDist()` | Sets the rendering distance.                             | number                        | `exports.Lights.setRenderDist(50)`                 |
| `setColor()`      | Sets the color using RGB integer values.                 | table (r, g, b), numbers      | `exports.Lights.setColor({r=255, g=100, b=50})`     |
| `setRange()`      | Sets the range.                                          | number                        | `exports.Lights.setRange(50.0)`                      |
| `setIntensity()`  | Sets the intensity.                                      | number                        | `exports.Lights.setIntensity(1.0)`                  |
| `setShadow()`     | Sets the shadow parameters.                              | number                        | `exports.Lights.setShadow(10.0)`                       |
