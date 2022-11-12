# DataBindingApp
Here databinding are shown with include and import functionality.</br>
**DataBinding** is a support library that allows you to bind UI components in your layouts to data sources in your app using a declarative format rather than programmatically.
## Data binding setup
Inside **build.gradle** file add this code
```
buildFeatures{
  dataBinding true
}
```
If you donot want to generate binding class add this inside root layout
```
tools: viewBindingIgnore = "true"
```
## Advantages of Data Binding
- Donot have to worry about refreshing the UI when underlying data sources changes.
# Output
![Ouput](https://user-images.githubusercontent.com/78687005/201484604-592e5559-777f-47ad-8aaf-7dd1c686382f.gif)
