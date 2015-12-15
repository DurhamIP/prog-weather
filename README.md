#Week 12 Bench Test Scenario: Climate Data

The UK Met Office provides historical climate data from a number of weather stations around the uk <http://www.metoffice.gov.uk/public/weather/climate-historic/#?tab=climateHistoric>

In preparation for the programming bench test which takes place during practical sessions of week 12 (i.e. second week of term 2, beginning 25/1/2016) you should try to implement the interfaces given. During the bench test itself you will adapt this code to solve some new problems, given by updated interfaces. You will have access to the code you have already written.

Download this repository from github and put the java interfaces into a new project. DO NOT CHANGE THE INTERFACE FILES as your work will be marked against the originals.

I recommend you try to complete the classes in the order
* Position
* Observation
* Station
* MetOffice

Make sure that your classes implement the relevant interfaces e.g.

```
public class Station implements StationInterface{
   // class definition here
}
```

While you are writing your classes you will get an compilation error `... is not abstract and does not override abstrect method ...`. This happens when you have not implemented all of the methods in the interface definition. One way round this is to provide 'stub' method definitions for each of the methods in the interface, with only a return statement if required e.g. in _Station_

```
public List<ObservationInterface> getObservations(){
   return null;
}
```

Replace the stub methods with real methods one at a time until the class is complete.

##Javadoc

Javadoc files for the interfaces have been created.

* [PositionInterface](doc/PositionInterface.html)
* [ObservationInterface](doc/ObservationInterface.html)
* [StationInterface](doc/StationInterface.html)
* [MetOfficeInterface](doc/MetOfficeInterface.html)
* [index](doc/index.html)