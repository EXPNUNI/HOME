---
layout: default
title: SetAttribute
parent: Script API
last_modified_date: now
---
# SetAttribute\(variable, value\)

SetAttribute\(\)

#### Parameters

variable : 속성값을 적용하고자하는 변수이름을 입력합니다.

value : 속성값을 입력합니다.

#### Return Value

none

#### Remarks

그래픽 객체의 속성값을 변경하는 함수입니다. 객체의 속성에 값을 할당합니다.

SetAttribute의 함수는 문자열형태로 변수명과 값을 입력하여 처리됩니다.

주) 스크립트 작성 위치 기반으로 해당 속성 변수에 대하여 설정합니다. 

ex) SVG 노드에 RECT 객체를 생성, RECT의 width값 변경시 

* SVG에 스크립트를 작성한 경우 : SetAttribute("ID_RECT.width", "10") 사용

* RECT 객체에 스크립트를 작성한 경우 : SetAttribute("width", "10") 사용


```lua
-- lua
SetAttribute("ID_RECT.width", "10")

-- equal expression
ID_RECT.width = 10
```

```js
// javascript
SetAttribute("ID_RECT.width", "10");

// equal expression
ID_RECT.width = 10;
```

#### 

#### Examples

```lua
-- lua
function _onmousedown()
    -- svg 하
    SetAttribute("ID_RECT.width", "10")
end
```

```js
// JavaScript
function _onmousedown()
{    
    SetAttribute("ID_RECT.width", "10");
}
```



