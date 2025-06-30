---
title: "Expressive Code スクロールテスト"
publishDate: "27 June 2025"
description: "Expressive Codeのスクロール機能をテストするための投稿"
tags: ["test", "expressive-code", "scroll"]
draft: true
---

## 横スクロールテスト

以下のコードブロックは非常に長い行を含んでおり、横スクロールが必要になるはずです：

```javascript
const veryLongFunctionNameThatExceedsTheContainerWidthAndRequiresHorizontalScrolling = (parameterWithVeryLongNameThatExceedsTheContainerWidth, anotherParameterWithVeryLongNameThatAlsoExceedsTheContainerWidth) => {
    return `This is a very long string that should definitely exceed the container width and require horizontal scrolling to see the full content. The string contains multiple words and should demonstrate the scrolling behavior of Expressive Code when useThemedScrollbars is set to false.`;
};
```

```typescript
interface VeryLongInterfaceNameThatExceedsTheContainerWidthAndRequiresHorizontalScrolling {
    propertyWithVeryLongNameThatExceedsTheContainerWidth: string;
    anotherPropertyWithVeryLongNameThatAlsoExceedsTheContainerWidth: number;
    yetAnotherPropertyWithEvenLongerNameThatDefinitelyExceedsTheContainerWidthAndRequiresScrolling: boolean;
}
```

```python
def very_long_function_name_that_exceeds_the_container_width_and_requires_horizontal_scrolling(parameter_with_very_long_name_that_exceeds_the_container_width, another_parameter_with_very_long_name_that_also_exceeds_the_container_width):
    return "This is a very long string that should definitely exceed the container width and require horizontal scrolling to see the full content"
```

```css
.very-long-css-class-name-that-exceeds-the-container-width-and-requires-horizontal-scrolling {
    background-color: rgba(255, 255, 255, 0.5);
    border: 1px solid rgba(0, 0, 0, 0.2);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 6px 20px rgba(0, 0, 0, 0.1);
    transform: translateX(100px) translateY(50px) scale(1.2) rotate(45deg);
}
```

## 通常の幅のコードブロック

比較用に、通常の幅のコードブロックも表示します：

```javascript
function normalFunction() {
    return "This is normal";
}
```

これらのコードブロックでスクロール動作を確認できます。