# Unity.EditorPrompt

Prompt the user for a string in Unity Editor

## Installation

Add the dependency to your `manifest.json`

```json
{
  "dependencies": {
    "jd.boiv.in.prompt": "https://github.com/starburst997/Unity.EditorPrompt.git"
  }
}
```

## Usage

![Screenshot](/Documentation~/Screenshot.png?raw=true)

```cs
var name = EditorPrompt.Show("New Biome", "Please enter name for the new Biome", "");
```

## Credits

Originally from [Vedran_M](https://discussions.unity.com/u/Vedran_M) on [Unity Forum](https://discussions.unity.com/t/is-there-a-way-to-input-text-using-a-unity-editor-utility/666472/9)