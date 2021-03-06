---
-api-id: P:Windows.UI.Xaml.Controls.InkToolbarPenButton.MinStrokeWidth
-api-type: winrt property
---

<!-- Property syntax
public double MinStrokeWidth { get;  set; }
-->

# Windows.UI.Xaml.Controls.InkToolbarPenButton.MinStrokeWidth

## -description
Gets or sets the minimum possible [Size](../windows.ui.input.inking/inkdrawingattributes_size.md) of an ink stroke.

For ballpoint pen and pencil strokes, [MinStrokeWidth](inktoolbarpenbutton_minstrokewidth.md) specifies both the minimum [Height](../windows.foundation/size.md) and [Width](../windows.foundation/size.md) of a [Rectangle](../windows.ui.input.inking/pentipshape.md) pen tip.

For highlighter strokes, [MinStrokeWidth](inktoolbarpenbutton_minstrokewidth.md) specifies the minimum height of a [Rectangle](../windows.ui.input.inking/pentipshape.md) pen tip, while [MinStrokeWidth](inktoolbarpenbutton_minstrokewidth.md)/3 specifies the minimum width.

Custom pen stroke dimensions can be set as required.

## -property-value
The maximum possible width of the ink stroke. The default is 0.

## -remarks

## -examples

## -see-also
[Pen and stylus interactions](http://msdn.microsoft.com/library/3da4f2d2-5405-42a1-9ed9-3a87bcd84c43), [Add an InkToolbar to a Universal Windows Platform (UWP) app](https://docs.microsoft.com/windows/uwp/input-and-devices/ink-toolbar), [Get Started Tutorial: Support ink in your UWP app](https://docs.microsoft.com/windows/uwp/get-started/ink-walkthrough), [MinStrokeWidthProperty](inktoolbarpenbutton_minstrokewidthproperty.md), [Ink sample (JavaScript)](http://go.microsoft.com/fwlink/p/?LinkID=620308), [Get Started Tutorial: Support ink in your UWP app](https://aka.ms/appsample-ink), [Coloring book sample](https://aka.ms/cpubsample-coloringbook), [Family notes sample](https://aka.ms/cpubsample-familynotessample)

