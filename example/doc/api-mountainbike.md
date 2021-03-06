# Module <!-- group --> `mountainbike`

Mountain bike module contains the `MountainBike` class. Mountain bikes are a kind of bike for cycling on rough terrain.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`transport::MountainBike`](#classtransport_1_1MountainBike)    | 
# class `transport::MountainBike` 

```
class transport::MountainBike
  : public transport::Bicycle
```  



Mountain bike implementation of a `[Bicycle](#classtransport_1_1Bicycle)`.

[MountainBike](#classtransport_1_1MountainBike) is an implementation of a [Bicycle](#classtransport_1_1Bicycle) providing a bike for cycling on rough terrain. Mountain bikes are pretty cool because they have stuff like **Suspension** (and you can even adjust it using SetSuspension). If you're looking for a bike for use on the road, you might be better off using a [RacingBike](#classtransport_1_1RacingBike) though.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public bool SetSuspension(double stiffness)` | 
`public template<typename BreakType>`  <br/>`inline bool ChangeBreak(BreakType breakType)` | 

## Members

#### `public bool SetSuspension(double stiffness)` 



Set suspension stiffness.  the suspension stiffness.

SetSuspension changes the stiffness of the suspension on the bike. The method will return false if the stiffness could not be adjusted.


#### Returns
true if the suspension was adjusted successfully, false otherwise.

#### `public template<typename BreakType>`  <br/>`inline bool ChangeBreak(BreakType breakType)` 



Change the break type.  the break type.  the type of the break.

ChangesBreak changes the type of break fitted to the bike. The method will return false if the break type could not be fitted.


#### Returns
true if the break was adjusted successfully. false otherise

