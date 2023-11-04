[Haiku Engine Documentation](../README.md) / [Exports](../modules.md) / [ui\_input\_keyboard/ui\_input\_keyboard](../modules/ui_input_keyboard_ui_input_keyboard.md) / UIInputKeyboard

# Class: UIInputKeyboard

[ui_input_keyboard/ui_input_keyboard](../modules/ui_input_keyboard_ui_input_keyboard.md).UIInputKeyboard

The `UIInputKeyboard` class represents a keyboard input widget.
It emit 'E_VALUE_CHANGED' when value changed.

## Hierarchy

- [`UIWidget`](ui_ui_widget$UIWidget.md)

  ↳ **`UIInputKeyboard`**

## Table of contents

### Methods

- [$moveCursor](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#$movecursor)
- [animate](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#animate)
- [appendStyles](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#appendstyles)
- [delete](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#delete)
- [focus](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#focus)
- [getId](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#getid)
- [getNode](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#getnode)
- [getPosition](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#getposition)
- [getScreenPosition](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#getscreenposition)
- [isEnabled](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#isenabled)
- [isFocused](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#isfocused)
- [isSelected](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#isselected)
- [isVisible](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#isvisible)
- [onAction](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#onaction)
- [setEnabled](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#setenabled)
- [setId](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#setid)
- [setPosition](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#setposition)
- [setSelected](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#setselected)
- [setValue](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#setvalue)
- [setVisible](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#setvisible)
- [unfocus](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#unfocus)
- [update](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#update)

### Properties

- [className](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#classname)
- [column](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#column)
- [id](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#id)
- [node](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#node)
- [row](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#row)
- [template](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#template)
- [value](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#value)

### Constructors

- [constructor](ui_input_keyboard_ui_input_keyboard$UIInputKeyboard.md#constructor)

## Methods

### $moveCursor

▸ **$moveCursor**(`direction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `direction` | ``"LEFT"`` \| ``"RIGHT"`` \| ``"UP"`` \| ``"DOWN"`` |

#### Returns

`void`

___

### animate

▸ **animate**(`animation`): `void`

The "animate" function trigger animation to the widget `node` HTMLElement.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `animation` | `string` | The `animation` parameter is a string that represents the name of the animation to be applied to the `node` HTMLElement. |

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[animate](ui_ui_widget$UIWidget.md#animate)

___

### appendStyles

▸ **appendStyles**(`styles`): `void`

The "appendStyles" function appends CSS styles to the `node` HTMLElement.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `styles` | `string` | The `styles` parameter is a string that represents CSS styles that you want to append to the `cssText` property of the `node` object. |

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[appendStyles](ui_ui_widget$UIWidget.md#appendstyles)

___

### delete

▸ **delete**(): `void`

The "delete" function free all resources.
Warning: you need to call this method to free allocation for this object.

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[delete](ui_ui_widget$UIWidget.md#delete)

___

### focus

▸ **focus**(): `void`

The "focus" function.

#### Returns

`void`

#### Overrides

[UIWidget](ui_ui_widget$UIWidget.md).[focus](ui_ui_widget$UIWidget.md#focus)

___

### getId

▸ **getId**(): `string`

The "getId" function returns the `ìd` property.

#### Returns

`string`

The `ìd`property.

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[getId](ui_ui_widget$UIWidget.md#getid)

___

### getNode

▸ **getNode**(): `HTMLDivElement`

The "getNode" function returns the root `node` HTMLElement of the widget.

#### Returns

`HTMLDivElement`

The `node` property.

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[getNode](ui_ui_widget$UIWidget.md#getnode)

___

### getPosition

▸ **getPosition**(): [`vec2`](../modules/core_global.md#vec2)

The "getPosition" function returns the relative x and y coordinates of the widget `node` HTMLElement.

#### Returns

[`vec2`](../modules/core_global.md#vec2)

The x and y coordinates of the node's position.

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[getPosition](ui_ui_widget$UIWidget.md#getposition)

___

### getScreenPosition

▸ **getScreenPosition**(): [`vec2`](../modules/core_global.md#vec2)

The "getScreenPosition" function returns the left and top coordinates of the widget `node` HTMLElement on
the screen.

#### Returns

[`vec2`](../modules/core_global.md#vec2)

The screen position.

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[getScreenPosition](ui_ui_widget$UIWidget.md#getscreenposition)

___

### isEnabled

▸ **isEnabled**(): `boolean`

The "isEnabled" function checks if widget is enabled or not.

#### Returns

`boolean`

A boolean value indicating if the widget is enabled or not.

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[isEnabled](ui_ui_widget$UIWidget.md#isenabled)

___

### isFocused

▸ **isFocused**(): `boolean`

The "isFocused" function checks if widget is focused.

#### Returns

`boolean`

A boolean value indicating if widget is focused or not.

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[isFocused](ui_ui_widget$UIWidget.md#isfocused)

___

### isSelected

▸ **isSelected**(): `boolean`

The "isSelected" function checks if widget is selected or not.

#### Returns

`boolean`

A boolean value indicating if the widget is selected or not.

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[isSelected](ui_ui_widget$UIWidget.md#isselected)

___

### isVisible

▸ **isVisible**(): `boolean`

The "isVisible" function checks if the widget is visible.

#### Returns

`boolean`

A boolean value indicating if widget is visible or not.

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[isVisible](ui_ui_widget$UIWidget.md#isvisible)

___

### onAction

▸ **onAction**(`actionId`): `void`

The "onAction" function.
It emits an event with the name 'E_VALUE_CHANGED' if the actionId is 'OK'.

#### Parameters

| Name | Type |
| :------ | :------ |
| `actionId` | `string` |

#### Returns

`void`

#### Overrides

[UIWidget](ui_ui_widget$UIWidget.md).[onAction](ui_ui_widget$UIWidget.md#onaction)

___

### setEnabled

▸ **setEnabled**(`enabled`): `void`

The "setEnabled" function sets the enabled state flag.
It is just to expose a convenient option to the user, this flag has not effect on the UI manager.
Nota bene: toggle the `u-disabled` class on `node`.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enabled` | `boolean` | The `enabled` parameter is a boolean value that determines whether the widget is enabled or disabled. |

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[setEnabled](ui_ui_widget$UIWidget.md#setenabled)

___

### setId

▸ **setId**(`id`): `void`

The "setId" function sets the id property.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `id` | `string` | A string representing the unique identifier to be set. |

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[setId](ui_ui_widget$UIWidget.md#setid)

___

### setPosition

▸ **setPosition**(`x`, `y`): `void`

The "setPosition" function sets the left and top position to the widget `node` HTMLElement.
Nota bene: works only if position is `absolute`.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `x` | `number` | The horizontal position of the element on the page. |
| `y` | `number` | The vertical position of the element on the page. |

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[setPosition](ui_ui_widget$UIWidget.md#setposition)

___

### setSelected

▸ **setSelected**(`selected`): `void`

The "setSelected" function sets the selected state flag.
It is just to expose a convenient option to the user, this flag has not effect on the UI manager.
Nota bene: toggle the `u-selected` class on `node`.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `selected` | `boolean` | The `selected` parameter is a boolean value that indicates whether the element should be selected or not. |

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[setSelected](ui_ui_widget$UIWidget.md#setselected)

___

### setValue

▸ **setValue**(`value`): `void`

The "setValue" function sets the input value.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `string` | The `value` parameter is a string that represents the new value to be set. |

#### Returns

`void`

___

### setVisible

▸ **setVisible**(`visible`): `void`

The "setVisible" function sets the visibility state.
Nota bene: toggle the `u-hidden` class on `node`.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `visible` | `boolean` | The `visible` parameter is a boolean value that determines whether the element should be visible or hidden. If `visible` is true, the element will be displayed, otherwise it will be hidden. |

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[setVisible](ui_ui_widget$UIWidget.md#setvisible)

___

### unfocus

▸ **unfocus**(): `void`

The "unfocus" function.

#### Returns

`void`

#### Overrides

[UIWidget](ui_ui_widget$UIWidget.md).[unfocus](ui_ui_widget$UIWidget.md#unfocus)

___

### update

▸ **update**(`ts`): `void`

The "update" function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ts` | `number` | The `ts` parameter stands for "timestep". |

#### Returns

`void`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[update](ui_ui_widget$UIWidget.md#update)

## Properties

### className

• **className**: `string`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[className](ui_ui_widget$UIWidget.md#classname)

___

### column

• **column**: `number`

___

### id

• **id**: `string`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[id](ui_ui_widget$UIWidget.md#id)

___

### node

• **node**: `HTMLDivElement`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[node](ui_ui_widget$UIWidget.md#node)

___

### row

• **row**: `number`

___

### template

• **template**: `string`

#### Inherited from

[UIWidget](ui_ui_widget$UIWidget.md).[template](ui_ui_widget$UIWidget.md#template)

___

### value

• **value**: `string`

## Constructors

### constructor

• **new UIInputKeyboard**()

The constructor.

#### Overrides

[UIWidget](ui_ui_widget$UIWidget.md).[constructor](ui_ui_widget$UIWidget.md#constructor)