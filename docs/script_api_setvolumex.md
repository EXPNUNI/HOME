---
layout: default
title: SetVolumeX
parent: Script API
last_modified_date: now
---
# SetVolumeX\(volume\)

SetVolumeX\(\)

#### Parameters

volume : 볼륨값을 입력합니다.

#### Return Value

none

#### Remarks

[PlaySoundX\(\)](/ScriptAPI\PlaySoundX.html), [StopSoundX\(\)](/ScriptAPI\StopSoundX.html)함수와 함께 사용됩니다.

```lua
-- lua
SetVolumeX(75)
```

```js
// javascript
SetVolumeX(75);
```

#### 

#### Examples

```lua
-- lua
function _onmousedown()
    SetVolumeX(75)
end
```

```js
// JavaScript
function _onmousedown()
{    
    SetVolumeX(75);
}
```



