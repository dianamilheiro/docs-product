---
tags: runtime-traditionalweb; 
summary: Fieldset labels groups of related interface elements and fields.
---

# Fieldset

<div class="info" markdown="1">

We’ve been working on this article. Please let us know how useful this new version is by voting.

</div>

You can use the Fieldset UI Pattern to group and label related information, such as a users personal details, improving the overall look and layout of your application.

![](<images/fieldset-1-ss.png>)

**How to use the Fieldset UI Pattern**

1. In Service Studio, in the Toolbox, search for `Fieldset`.

    The Fieldset widget is displayed.

    ![](<images/fieldset-6-ss.png>)

    If the UI widget does not display, it may be because you used a ready-made app, which deletes unused widgets from the module. To make additional widgets available in your app:

    a. Go to **Module > Manage dependencies**.

    b. Search for and select the relevant Producer, for example OutSystemsUI. Ensure Show All is selected. 

    c. On the Public elements for the selected Producer displayed on the right, ensure Show All is selected.
    
    d. Search for and select the element you want to add, and click **Apply**. 
    
    e. In Service Studio, in the Toolbox, search for the widget again.

1. From the Toolbox, drag the Fieldset widget into the Main Content area of your application's screen.

    ![](<images/fieldset-7-ss.png>)

1. On the **Properties** tab, set the Title property.

    In the following example, we set the Title to `Basic Information`.

    ![](<images/fieldset-5-ss.png>)

1. Add the relevant content to the placeholder, for example, text boxes and labels.

    ![](<images/fieldset-8-ss.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| Properties | Description |
|---|---|
| Title (Text): Mandatory   |  The Fieldset title.  <p>Examples <ul><li>_"Basic Information"_ - the title is set to Basic Information</li></ul></p> | 
| ExtendedClass (Text): Optional  | Adds custom style classes to the Pattern. You define your [custom style classes](../../../../../develop/ui/look-feel/css.md) in your application using CSS. <p>Examples <ul><li>_Blank_ - No custom styles are added (default value).</li><li>_"myclass"_ - Adds the _myclass style_ to the UI styles being applied.</li><li>_"myclass1 myclass2"_ - Adds the _myclass1_ and _myclass2_ styles to the UI styles being applied.</li></ul></p>You can also use the classes available on the OutSystems UI. For more information, see the [OutSystems UI Live Style Guide](https://outsystemsui.outsystems.com/StyleGuidePreview/Styles). |
