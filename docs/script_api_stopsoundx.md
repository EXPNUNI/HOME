---
layout: default
title: StopSoundX
parent: Script API
last_modified_date: now
---
# StopSoundX\(wave\)

StopSoundX\(\)

#### Parameters

wave : 재생중인 파일이름을 입력합니다.

#### Return Value

none

#### Remarks

[PlaySoundX\(\)](/ScriptAPI\PlaySoundX.html)함수를 통하여 재생중인 소리를 정지합니다.

```lua
-- lua
StopSoundX("resource\\alarm.wav")
```

```js
// javascript
StopSoundX("resource\\alarm.wav");
```

#### 

#### Examples

```lua
-- lua
function _onmousedown()
    StopSoundX("resource\\alarm.wav")
end
```

```js
// JavaScript
function _onmousedown()
{    
    StopSoundX("resource\\alarm.wav");
}
```



