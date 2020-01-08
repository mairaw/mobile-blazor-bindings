---
title: 'Roadmap'
---

# Roadmap

## Overview

As an experimental project, there are several active areas of development and we're looking for your feedback to help set the direction for this project.

## Areas for possible improvement

* [Add support for Hot Reload](https://github.com/xamarin/MobileBlazorBindings/issues/23)
* Support for inline text and markup in issues [MobileBlazorBindings#26](https://github.com/xamarin/MobileBlazorBindings/issues/26) and [MobileBlazorBindings#27](https://github.com/xamarin/MobileBlazorBindings/issues/27)
* Implement more wrappers for Xamarin.Forms elements. The most common Xamarin.Forms elements are available for use with Experimental Mobile Blazor Bindings, but there are more still to come. Follow [this issue](https://github.com/xamarin/MobileBlazorBindings/issues/5) on GitHub to track the availability of components, or file a new issue with any feature suggestions.
* The current elements are mostly direct wrappers of Xamarin.Forms components. An open question is whether there should be components that are more abstract and/or match other patterns such as web-based patterns.
* Better support for the `Shell` component.
* Support URL-based navigation, both with the `Shell` component, and using Blazor's `@page` directive URL support.
* Improved handling of modal dialogs and pop-ups. There is support for basic modal dialogs using the `ModalContainer` component, as seen in the [Todo app sample](https://github.com/xamarin/MobileBlazorBindings/blob/master/samples/MobileBlazorBindingsTodoSample/MobileBlazorBindingsTodo/TodoEntry.razor#L12-L14).