# How to set the image to Ribbon Button in WPF Ribbon control?

This sample showcases how to set the image to Ribbon Button in [WPF Ribbon](https://www.syncfusion.com/wpf-ui-controls/ribbon) control.

The WPF Ribbon control accommodates all the tools required for an application in a single, easy-to-navigate user interface like Microsoft Office. Ribbon buttons provide basic functionalities and allow customization of image size and layout.

---

## Working with Ribbon Button Image Size
Ribbon items such as **RibbonButton**, **SplitButton**, and **DropDownButton** support image customization using `SizeForm` and `IconStretch` properties.

### SizeForm Options:
- **Large**: Large button with large image and text.
- **Small**: Small button with small image and text.
- **ExtraSmall**: Extra small button with image only.

### IconStretch Options:
- **Fill**: Image fills the destination without preserving aspect ratio.
- **Uniform**: Image resizes uniformly to fit.
- **UniformToFill**: Image resizes uniformly to fill.
- **None**: Original image size is preserved.

Example:
```xml
<syncfusion:RibbonButton Label="Save" SizeForm="Large" IconStretch="Uniform" LargeIcon="Images/save32.png" />
```

---

## Adaptive Ribbon Layout
The ribbon control dynamically resizes as the window width changes. Items switch from **Large** → **Small** → **ExtraSmall**, and finally collapse into a dropdown.

Enable responsive resizing:
```xml
IsAutoSizeFormEnabled="True" CollapseImage="Images/collapse.png"
```

---

For more details, refer to [KB Article](https://support.syncfusion.com/kb/article/9426/how-to-working-with-ribbon-button-image-size-in-wpf-ribbon-control).


## Documentation
- [KB Article](https://support.syncfusion.com/kb/article/9426/how-to-working-with-ribbon-button-image-size-in-wpf-ribbon-control)
- [Syncfusion WPF Ribbon Documentation](https://help.syncfusion.com/wpf/ribbon/gettingstarted#add-ribbonbutton)
