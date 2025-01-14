[@puppeteer/replay](../README.md) / [Schema](../modules/Schema.md) / ClickStep

# Interface: ClickStep

[Schema](../modules/Schema.md).ClickStep

## Hierarchy

- [`ClickAttributes`](Schema.ClickAttributes.md)

- [`StepWithSelectors`](Schema.StepWithSelectors.md)

  ↳ **`ClickStep`**

## Table of contents

### Properties

- [assertedEvents](Schema.ClickStep.md#assertedevents)
- [button](Schema.ClickStep.md#button)
- [deviceType](Schema.ClickStep.md#devicetype)
- [duration](Schema.ClickStep.md#duration)
- [frame](Schema.ClickStep.md#frame)
- [offsetX](Schema.ClickStep.md#offsetx)
- [offsetY](Schema.ClickStep.md#offsety)
- [selectors](Schema.ClickStep.md#selectors)
- [target](Schema.ClickStep.md#target)
- [timeout](Schema.ClickStep.md#timeout)
- [type](Schema.ClickStep.md#type)

## Properties

### assertedEvents

• `Optional` **assertedEvents**: [`NavigationEvent`](Schema.NavigationEvent.md)[]

#### Inherited from

[StepWithSelectors](Schema.StepWithSelectors.md).[assertedEvents](Schema.StepWithSelectors.md#assertedevents)

#### Defined in

[Schema.ts:33](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L33)

___

### button

• `Optional` **button**: ``"primary"`` \| ``"auxiliary"`` \| ``"secondary"`` \| ``"back"`` \| ``"forward"``

Defaults to 'primary' if the device type is a mouse.

#### Inherited from

[ClickAttributes](Schema.ClickAttributes.md).[button](Schema.ClickAttributes.md#button)

#### Defined in

[Schema.ts:62](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L62)

___

### deviceType

• `Optional` **deviceType**: ``"mouse"`` \| ``"pen"`` \| ``"touch"``

Pointer type for the event. Defaults to 'mouse'.

#### Inherited from

[ClickAttributes](Schema.ClickAttributes.md).[deviceType](Schema.ClickAttributes.md#devicetype)

#### Defined in

[Schema.ts:58](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L58)

___

### duration

• `Optional` **duration**: `number`

Delay (in ms) between the mouse up and mouse down of the click. Defaults to
50ms.

#### Defined in

[Schema.ts:85](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L85)

___

### frame

• `Optional` **frame**: [`FrameSelector`](../modules/Schema.md#frameselector)

Defaults to main frame

#### Inherited from

[StepWithSelectors](Schema.StepWithSelectors.md).[frame](Schema.StepWithSelectors.md#frame)

#### Defined in

[Schema.ts:47](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L47)

___

### offsetX

• **offsetX**: `number`

in px, relative to the top-left corner of the element content box. Defaults
to the center of the element

#### Inherited from

[ClickAttributes](Schema.ClickAttributes.md).[offsetX](Schema.ClickAttributes.md#offsetx)

#### Defined in

[Schema.ts:67](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L67)

___

### offsetY

• **offsetY**: `number`

in px, relative to the top-left corner of the element content box. Defaults
to the center of the element

#### Inherited from

[ClickAttributes](Schema.ClickAttributes.md).[offsetY](Schema.ClickAttributes.md#offsety)

#### Defined in

[Schema.ts:72](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L72)

___

### selectors

• **selectors**: [`Selector`](../modules/Schema.md#selector)[]

#### Inherited from

[StepWithSelectors](Schema.StepWithSelectors.md).[selectors](Schema.StepWithSelectors.md#selectors)

#### Defined in

[Schema.ts:51](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L51)

___

### target

• `Optional` **target**: `string`

Defaults to main

#### Inherited from

[StepWithSelectors](Schema.StepWithSelectors.md).[target](Schema.StepWithSelectors.md#target)

#### Defined in

[Schema.ts:40](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L40)

___

### timeout

• `Optional` **timeout**: `number`

#### Inherited from

[StepWithSelectors](Schema.StepWithSelectors.md).[timeout](Schema.StepWithSelectors.md#timeout)

#### Defined in

[Schema.ts:32](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L32)

___

### type

• **type**: ``"click"``

#### Overrides

[StepWithSelectors](Schema.StepWithSelectors.md).[type](Schema.StepWithSelectors.md#type)

#### Defined in

[Schema.ts:80](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L80)
