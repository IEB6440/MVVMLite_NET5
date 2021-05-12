# MVVMLite_NET5
This package contains a set of tools for working with MVVM


SAMPLE

Use ObservableObject class as parent for any Models classes (ViewModels)
Namespace  IEB6440.MVVMLite.NET5.Connector


To connect Run commands connect IEB6440.MVVMLite.NET5.Commands namespace
Create a object Run or RunWithParameter classes and send method as action to object initializer

Example:

Run command = new Run(MyMethod);

private void MyMethod(){
  
}

RunWithParameter command = new RunWithParameter(MyMethod);

private void MyMethod(string parameter){
  
}
