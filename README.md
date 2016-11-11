# Prism.WinForms

Reduced version of Prism.WPF that works in Windows.Forms.

### Includes: 
* Unity bootstraper
* Modularity

## What is Prism ?

Prism is a framework for building loosely coupled, maintainable, and testable XAML applications in WPF, Windows 10 UWP, and Xamarin Forms. Separate releases are available for each platform and those will be developed on independent timelines. Prism provides an implementation of a collection of design patterns that are helpful in writing well-structured and maintainable XAML applications, including MVVM, dependency injection, commands, EventAggregator, and others. Prism's core functionality is a shared code base in a Portable Class Library targeting these platforms. Those things that need to be platform specific are implemented in the respective libraries for the target platform. Prism also provides great integration of these patterns with the target platform. For example, Prism for UWP and Xamarin Forms allows you to use an abstraction for navigation that is unit testable, but that layers on top of the platform concepts and APIs for navigation so that you can fully leverage what the platform itself has to offer, but done in the MVVM way.

Prism 6 is a fully open source version of the Prism guidance originally produced by Microsoft patterns & practices. The core team members were all part of the p&p team that developed Prism 1 through 5, and the effort has now been turned over to the open source community to keep it alive and thriving to support the .NET community. There are thousands of companies who have adopted previous versions of Prism for WPF, Silverlight, and Windows Runtime, and we hope they will continue to move along with us as we continue to evolve and enhance the framework to keep pace with current platform capabilities and requirements.

For more info visit the [Prism][3] repository in github.

## Requeriments

* [Prism.Core][1]
* [Unity Container][2]

[1]: https://www.nuget.org/packages/Prism.Core/
[2]: https://www.nuget.org/packages/Unity/
[3]: https://github.com/PrismLibrary/Prism

