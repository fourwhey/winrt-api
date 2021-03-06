---
-api-id: P:Windows.Services.Maps.MapRouteLeg.BoundingBox
-api-type: winrt property
---

<!-- Property syntax
public Windows.Devices.Geolocation.GeoboundingBox BoundingBox { get; }
-->

# Windows.Services.Maps.MapRouteLeg.BoundingBox

## -description
Gets the bounding box that contains the route leg.

## -property-value
The bounding box that contains the route leg.

## -remarks
If you want to display this bounding box in the [MapControl](../windows.ui.xaml.controls.maps/mapcontrol.md), use one of the overloads of the [TrySetViewAsync](../windows.ui.xaml.controls.maps/mapcontrol_trysetviewasync.md) method that accepts a [GeoboundingBox](../windows.devices.geolocation/geoboundingbox.md) as input.

## -examples

## -see-also
[Display  routes and directions on a map](http://msdn.microsoft.com/library/bbb4c23a-8f10-41d1-81ea-271be01aed81)