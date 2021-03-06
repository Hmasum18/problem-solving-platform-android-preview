# Preview

#### current preview duration 2 min 15 sec. [click here](https://youtu.be/Gi9BSXA6JHg) to see the preview in youtube.

![preview](readMe_assets/preveiws/preview1.gif)

---

# Development

- Minimum SDK level 21
- Language : <a href="https://www.oracle.com/java/technologies/">JAVA</a>
- <a href="https://developer.android.com/jetpack">Jetpack</a>
  - <a href="https://www.youtube.com/watch?v=Y0Cs2MQxyIs&list=PLWz5rJ2EKKc9mxIBd0DRw9gwXuQshgmn2&index=12">Navigation component</a>  & <a href="https://developer.android.com/guide/navigation/navigation-design-graph">Navigation Graph</a>- used to achieve single Activity Architecture.([click here](https://developer.android.com/guide/navigation/navigation-migrate) to learn more)
  - <a href="https://www.youtube.com/watch?v=OMcDk2_4LSk&list=PLWz5rJ2EKKc9mxIBd0DRw9gwXuQshgmn2&index=7">LiveData</a> - to observe for change in data.
  - [Lifecycle](https://developer.android.com/guide/components/activities/activity-lifecycle) - dispose of observing data when lifecycle state changes.
  - <a href="https://www.youtube.com/watch?v=5qlIPTDE274&list=PLWz5rJ2EKKc9mxIBd0DRw9gwXuQshgmn2&index=6">ViewModel</a> - UI related data holder, lifecycle aware.
  - <a href="https://www.youtube.com/watch?v=SKWh4ckvFPM&list=PLWz5rJ2EKKc9mxIBd0DRw9gwXuQshgmn2&index=5">Room Persistence</a> - construct a database using the abstract layer.
  - <a href="https://developer.android.com/topic/libraries/view-binding">View Binding</a> - instead of finding views by id as it is safer than findViewById.
  - [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview) with [ListAdapter](https://developer.android.com/reference/kotlin/androidx/recyclerview/widget/ListAdapter) to show the changing topic, series , problem and user submission data
- Architecture
  - [MVVM](https://developer.android.com/jetpack/guide#recommended-app-arch)(Model-View-View Model)
  - Repository Pattern
  - [Single Activity](https://www.youtube.com/watch?v=2k8x8V77CrU) multiple fragments.
- <a href="https://square.github.io/retrofit/">Retrofit2</a> - construct the REST APIs and paging network data.
- <a href="https://github.com/bumptech/glide">Glide</a> - loading image from URL.
- <a href ="https://www.material.io/develop/android">Material-Components and Theming</a> - Material components  like cardView, chip etc are used to make UI better.
- <a href="https://noties.io/Markwon/">Markwon</a> - for markdown support to make problem board better.
- <a href="https://github.com/PhilJay/MPAndroidChart">MPAndroidChart</a>  - to show the user statistics in charts.

---

# Architecture 
Our App is based on Single Activity and MVVM architecture and repositories pattern.

### <u>Current Navigation graph</u>  

<img src="https://github.com/Hmasum18/problem-solving-platform-android-preview/blob/master/readMe_assets/images/navigation_graph.png" width="700" />

### <u>Architecture Diagram</u>

<img src="https://github.com/Hmasum18/problem-solving-platform-android-preview/blob/master/readMe_assets/images/mvvm.png" width="700" />

---

# Remote data source:
Firebase firestore and Our own server(Nodejs![]() + Postgresql![]())
