# Mobile Network CourseWorks

## Model View Controller

Model–view–controller (MVC) is an architectural pattern commonly used for developing user interfaces that divides an application into three interconnected parts. This is done to separate internal representations of information from the ways information is presented to and accepted from the user. The MVC design pattern decouples these major components allowing for efficient code reuse and parallel development.
Traditionally used for desktop graphical user interfaces (GUIs), this architecture has become popular for designing web applications and even mobile, desktop and other clients.  Popular programming languages like Java, C#, Ruby, PHP and others have popular MVC frameworks that are currently being used in web application development straight out of the box.
MVC Pattern stands for Model-View-Controller Pattern. This pattern is used to separate application's concerns.

1. Model - Model represents an object or JAVA POJO carrying data. It can also have logic to update controller if its data changes.

2. View - View represents the visualization of the data that model contains.

3. Controller - Controller acts on both model and view. It controls the data flow into model object and updates the view whenever data changes. It keeps view and model separate.

# IMPLEMENTATION

### Use in web applications

Although originally developed for desktop computing, MVC has been widely adopted as an architecture for World Wide Web applications in major programming languages. Several web frameworks have been created that enforce the pattern. These software frameworks vary in their interpretations, mainly in the way that the MVC responsibilities are divided between the client and server.

Some web MVC frameworks take a thin client approach that places almost the entire model, view and controller logic on the server. This is reflected in frameworks such as Django, Rails and ASP.NET MVC. In this approach, the client sends either hyperlink requests or form submissions to the controller and then receives a complete and updated web page (or other document) from the view; the model exists entirely on the server. Other frameworks such as AngularJS, EmberJS, Vue.js and Backbone allow the MVC components to execute partly on the client.

# Goals of MVC

## Simultaneous development

Because MVC decouples the various components of an application, developers are able to work in parallel on different components without impacting or blocking one another. For example, a team might divide their developers between the front-end and the back-end. The back-end developers can design the structure of the data and how the user interacts with it without requiring the user interface to be completed. Conversely, the front-end developers are able to design and test the layout of the application prior to the data structure being available.

## Code reuse

By creating components that are independent of one another, developers are able to reuse components quickly and easily in other applications. The same (or similar) view for one application can be refactored for another application with different data because the view is simply handling how the data is being displayed to the user.

## Advantages & disadvantages

### Advantages

   - Simultaneous development – Multiple developers can work simultaneously on the model, controller and views.
    High cohesion – MVC enables logical grouping of related actions on a controller together. The views for a specific model are also grouped together.
   - Low coupling – The very nature of the MVC framework is such that there is low coupling among models, views or controllers
   - Ease of modification – Because of the separation of responsibilities, future development or modification is easier
  - Multiple views for a model – Models can have multiple views

## Disadvantages

    - Code navigability – The framework navigation can be complex because it introduces new layers of abstraction and requires users to adapt to the decomposition criteria of MVC.
    - Multi-artifact consistency – Decomposing a feature into three artifacts causes scattering. Thus, requiring developers to maintain the consistency of multiple representations at once.
    - Pronounced learning curve – Knowledge on multiple technologies becomes the norm. Developers using MVC need to be skilled in multiple technologies.



