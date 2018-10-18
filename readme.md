# Harmonised Entities

## Overview

Data interoperability has been identified as a technical barrier that prohibits the realisation of the full potential value of IoT data.
To help address that problem, in this document data models are defined of entities or things that are commonly used in IoT applications.
The definitions of the data entities have been developed through contributions from participating mobile operators and aligned with existing industry work and namespaces where possible,
for example, oneM2M in Smart Home, OASC for Smart Cities and schema.org for generic entities.

## Scope

This resource specifies harmonised data models that have been developed by members of the [GSMA IoT Big Data Ecosystem Project](https://www.gsma.com/iot/iot-big-data/).
The harmonised data models are expected to evolve over time, potentially new entities will be added and entity definitions changed.
Contributions are welcome from the wider developer community to develop and update the data entities.

## Vertical Segments

The harmonised data entities below originate from and are used in the following industry verticals (or IoT Domains):

* Agriculture
* Automotive
* Environment
* Industry
* Smart City
* Smart Home


| Entity Name | Overview | Context Definition | Example Entity |
|:--- |:--- |:--- |:--- |
| **Agri Crop** | This entity contains a harmonised description of a generic crop. This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Agri-Crop.md) | [Context example.](examples/Agri-Crop-context.jsonld) | [Entity example.](examples/Agri-Crop.jsonld) |
| **Agri Greenhouse** | This entity contains a harmonised description of the conditions recorded within a generic greenhouse, a type of AgriParcel. This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Agri-Greenhouse.md) | [Context example.](examples/Agri-Greenhouse-context.jsonld) | [Entity example.](examples/Agri-Greenhouse.jsonld) |
| **Agri Parcel** | This entity contains a harmonised description of a generic parcel of land. This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Agri-Parcel.md) | [Context example.](examples/Agri-Parcel-context.jsonld) | [Entity example.](examples/Agri-Parcel.jsonld) |
| **Agri Parcel Operation** | This entity contains a harmonised description of a generic operations performed on a parcel of land. This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Agri-Parcel-Operation.md) | [Context example.](examples/Agri-Parcel-Operation-context.jsonld) | [Entity example.](examples/Agri-Parcel-Operation.jsonld) |
| **Agri Parcel Record** | This entity contains a harmonised description of the conditions recorded on a generic parcel of land. This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Agri-Parcel-Record.md) | [Context example.](examples/Agri-Parcel-Record-context.jsonld) | [Entity example.](examples/Agri-Parcel-Record.jsonld) |
| **Agri Pest** | This entity contains a harmonised description of an agricultural pest. This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Agri-Pest.md) | [Context example.](examples/Agri-Pest-context.jsonld) | [Entity example.](examples/Agri-Pest.jsonld) |
| **Agri Product Type** | This entity contains a harmonised description of a generic agricultural product type. This entity is primarily associated with the agricultural vertical and related IoT applications. The AgriProductType includes a hierarchical structure that allows product types to be grouped in a flexible way. [Specification.](definitions/Agri-Product-Type.md) | [Context example.](examples/Agri-Product-Type-context.jsonld) | [Entity example.](examples/Agri-Product-Type.jsonld) |
| **Agri Soil** | This entity contains a harmonised description of soil. This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Agri-Soil.md) | [Context example.](examples/Agri-Soil-context.jsonld) | [Entity example.](examples/Agri-Soil.jsonld) |
| **Air Quality Observed** | This entity contains a harmonised description of the air quality observed at a particular location and time. This entity is primarily associated with the vertical segment of the environment and may also be used in smart homes, smart cities, agriculture, industry and related IoT applications. [Specification.](definitions/Air-Quality-Observed.md) | [Context example.](examples/Air-Quality-Observed-context.jsonld) | [Entity example.](examples/Air-Quality-Observed.jsonld) |
| **Building** | This entity contains a harmonised description of a building. This entity is associated with the vertical segments of smart homes, smart cities, industry and related IoT applications. [Specification.](definitions/Building.md) | [Context example.](examples/Building-context.jsonld) | [Entity example.](examples/Building.jsonld) |
| **Building Operation** | This entity contains a harmonised description of a generic operation (related to smart buildings) applied to the referenced building. The building operation contains dynamic data reported by, or associated with a building or operations applicable to the building. This entity is associated with the vertical segments of smart homes, smart cities, industry and related IoT applications. [Specification.](definitions/Building-Operation.md) | [Context example.](examples/Building-Operation-context.jsonld) | [Entity example.](examples/Building-Operation.jsonld) |
| **Building Type** | This entity contains a harmonised description of a generic building type. This entity is associated with the vertical segments of smart home, smart cities, industry and related IoT applications. The building type includes a hierarchical structure that allows building types to be grouped in a flexible way. [Specification.](definitions/Building-Type.md) | [Context example.](examples/Building-Type-context.jsonld) | [Entity example.](examples/Building-Type.jsonld) |
| **Device** | This entity contains a harmonised description of a generic device. This entity provides an essentially static description of a generic device and is therefore applicable to all IoT segments and related IoT applications. [Specification.](definitions/Device.md) | [Context example.](examples/Device-context.jsonld) | [Entity example.](examples/Device.jsonld) |
| **Device Model** | This entity contains a harmonised description of a generic device model and is therefore applicable to all IoT segments and related IoT applications. The Device Model includes an optional hierarchical structure that allows device types to be grouped in a flexible way. [Specification.](definitions/Device-Model.md) | [Context example.](examples/Device-Model-context.jsonld) | [Entity example.](examples/Device-Model.jsonld) |
| **Device Operation** | This entity contains a harmonised description of a generic device operation entity. The device operation entity contains dynamic data reported by a device and is therefore applicable to all IoT segments and related IoT applications. [Specification.](definitions/Device-Operation.md) | [Context example.](examples/Device-Operation-context.jsonld) | [Entity example.](examples/Device-Operation.jsonld) |
| **Environment Observed** | This entity contains a harmonised description of the environmental conditions observed at a particular location and time. This entity is primarily associated with the vertical segment of the environment and agriculture but may also be used in smart home, smart cities, industry and related IoT applications. [Specification.](definitions/Environment-Observed.md) | [Context example.](examples/Environment-Observed-context.jsonld) | [Entity example.](examples/Environment-Observed.jsonld) |
| **Fleet Vehicle** | This entity contains a harmonised description of a generic fleet vehicle such as a delivery vehicle, an ambulance or a postal vehicle. This entity is primarily associated with the vertical segment of the transport and logistics but may also be used many other related IoT applications. [Specification.](definitions/Fleet-Vehicle.md) | [Context example.](examples/Fleet-Vehicle-context.jsonld) | [Entity example.](examples/Fleet-Vehicle.jsonld) |
| **Fleet Vehicle Operation** | This entity contains a harmonised description of a generic fleet vehicle operation such as a delivery, or a postal collection. This entity is primarily associated with the vertical segment of the transport and logistics but may also be used many other related IoT applications. [Specification.](definitions/Fleet-Vehicle-Operation.md) | [Context example.](examples/Fleet-Vehicle-Operation-context.jsonld) | [Entity example.](examples/Fleet-Vehicle-Operation.jsonld) |
| **Fleet Vehicle Status** | This entity contains a harmonised description of the status of a generic fleet vehicle. This entity is primarily associated with the vertical segment of the transport and logistics but may also be used many other related IoT applications. [Specification.](definitions/Fleet-Vehicle-Status.md) | [Context example.](examples/Fleet-Vehicle-Status-context.jsonld) | [Entity example.](examples/Fleet-Vehicle-Status.jsonld) |
| **Machine** | This entity contains a harmonised description of an industrial machine for example for use in CAM (Computer Aided Manufacturing). This entity provides an essentially static description of a generic automation machine. This entity is primarily associated with the industry segment in the automated manufacturing industry, including CNC (Computer Numerical Control) machines, 3D printers and all kinds of industrial robots. [Specification.](definitions/Machine.md) | [Context example.](examples/Machine-context.jsonld) | [Entity example.](examples/Machine.jsonld) |
| **Machine Model** | This entity contains a harmonised description of a generic machine model. This entity is primarily associated with the industry segment and related IoT applications. The machineModel includes a hierarchical structure that allows machine models to be grouped in a flexible way. [Specification.](definitions/Machine-Model.md) | [Context example.](examples/Machine-Model-context.jsonld) | [Entity example.](examples/Machine-Model.jsonld) |
| **Machine Operation** | This entity contains a harmonised description of a generic machine operation. This entity is primarily associated with the industry segment and related IoT applications. Each MachineOperation instance will be related to a specific Machine instance. [Specification.](definitions/Machine-Operation.md) | [Context example.](examples/Machine-Operation-context.jsonld) | [Entity example.](examples/Machine-Operation.jsonld) |
| **Market Price Forecast** | This entity contains a harmonised description of a generic commodity, crop or product price forecast that varies over time (a spot price forecast). This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Market-Price-Forecast.md) | [Context example.](examples/Market-Price-Forecast-context.jsonld) | [Entity example.](examples/Market-Price-Forecast.jsonld) |
| **Market Price Observed** | This entity contains a harmonised description of a generic commodity, crop or product price that varies over time (a spot price). This entity is primarily associated with the agricultural vertical and related IoT applications. [Specification.](definitions/Market-Price-Observed.md) | [Context example.](examples/Market-Price-Observed-context.jsonld) | [Entity example.](examples/Market-Price-Observed.jsonld) |
| **Point of Interest** | This entity contains a harmonised geographic description of a Point of Interest. This entity is used in applications that use spatial data and is applicable to Automotive, Environment, Industry and Smart City vertical segments and related IoT applications. [Specification.](definitions/Point-of-Interest.md) | [Context example.](examples/Point-of-Interest-context.jsonld) | [Entity example.](examples/Point-of-Interest.jsonld) |
| **Product** | This entity contains a harmonised description of a generic product. This entity is primarily associated with products and supply chains. It is based on the GS1 standard available at http://gs1.org/voc/Product [Specification.](definitions/Product.md) | [Context example.](examples/Product-context.jsonld) | [Entity example.](examples/Product.jsonld) |
| **Product Record** | This entity contains a harmonised description of the conditions recorded as a product (generally a physical instance of a product) moves through the supply chain. This entity is primarily associated with the retail supply vertical and related IoT applications. [Specification.](definitions/Product-Record.md) | [Context example.](examples/Product-Record-context.jsonld) | [Entity example.](examples/Product-Record.jsonld) |
| **Product Type** | This entity contains a harmonised description of a generic product type. This entity is primarily associated with the product supply chain verticals and related IoT applications. The ProductType includes a hierarchical structure that allows product types to be grouped in a flexible way. [Specification.](definitions/Product-Type.md) | [Context example.](examples/Product-Type-context.jsonld) | [Entity example.](examples/Product-Type.jsonld) |
| **Recogniser Input** | This entity contains a generic model for an input to an AI/ Machine Learning based image/audio recogniser [Specification.](definitions/Recogniser-Input.md) | [Context example.](examples/Recogniser-Input-context.jsonld) | [Entity example.](examples/Recogniser-Input.jsonld) |
| **Recogniser Result** | This entity contains a generic model for the resulting outputs from an AI/ Machine Learning based image/audio recogniser where multiple features are processed. [Specification.](definitions/Recogniser-Result.md) | [Context example.](examples/Recogniser-Result-context.jsonld) | [Entity example.](examples/Recogniser-Result.jsonld) |
| **Recogniser Simple Result** | This entity contains a generic model for a simple result output from an AI/ Machine Learning based image/audio recogniser [Specification.](definitions/Recogniser-Simple-Result.md) | [Context example.](examples/Recogniser-Simple-Result-context.jsonld) | [Entity example.](examples/Recogniser-Simple-Result.jsonld) |
| **Road** | This entity contains a harmonised geographic and contextual description of a Road. Roads are made up of one or more RoadSegment entities. This entity is primarily associated with the Automotive and Smart City vertical segments and related IoT applications. [Specification.](definitions/Road.md) | [Context example.](examples/Road-context.jsonld) | [Entity example.](examples/Road.jsonld) |
| **Road Segment** | This entity contains a harmonised geographic and contextual description of a RoadSegment. A collection of RoadSegments are used to describe a Road. This entity is primarily associated with the Automotive and Smart City vertical segments and related IoT applications. [Specification.](definitions/Road-Segment.md) | [Context example.](examples/Road-Segment-context.jsonld) | [Entity example.](examples/Road-Segment.jsonld) |
| **Smart Meter** | This entity contains a harmonised description of a Smart Meter, generally applicable for Smart Homes, Industry, Cities and Agriculture. It is designed to be a base for smart meter observations [Specification.](definitions/Smart-Meter.md) | [Context example.](examples/Smart-Meter-context.jsonld) | [Entity example.](examples/Smart-Meter.jsonld) |
| **Smart Meter Observed** | This entity contains a harmonised description of a Smart Meter Observation, generally applicable for Smart Homes, Industry, Cities and Agriculture. [Specification.](definitions/Smart-Meter-Observed.md) | [Context example.](examples/Smart-Meter-Observed-context.jsonld) | [Entity example.](examples/Smart-Meter-Observed.jsonld) |
| **Subscriber** | This entity contains a harmonised description of a subscriber to a service. This entity is primarily associated with the Smart Home/ Smart Buildings vertical segments and related IoT applications. [Specification.](definitions/Subscriber.md) | [Context example.](examples/Subscriber-context.jsonld) | [Entity example.](examples/Subscriber.jsonld) |
| **Subscription Service** | This entity contains a harmonised description of a subscription service. This entity is primarily associated with the Smart Home/ Smart Building vertical segments and related IoT applications. [Specification.](definitions/Subscription-Service.md) | [Context example.](examples/Subscription-Service-context.jsonld) | [Entity example.](examples/Subscription-Service.jsonld) |
| **UAV** | This entity contains a harmonised description of a specific Unmanned Aerial Vehicle (UAV). This entity is primarily associated with UAV command and control and related UAV transport applications. [Specification.](definitions/UAV.md) | [Context example.](examples/UAV-context.jsonld) | [Entity example.](examples/UAV.jsonld) |
| **UAV ADSB** | This entity contains a harmonised description of a generic UAV Automatic Dependent Surveillance–Broadcast. This entity is primarily associated with the control and management of Unmanned Aerial Vehicles. Each UAVADSB instance will be related to a specific UAV instance. [Specification.](definitions/UAV-ADSB.md) | [Context example.](examples/UAV-ADSB-context.jsonld) | [Entity example.](examples/UAV-ADSB.jsonld) |
| **UAV Event** | The UAVEvent records the incursion of a specific UAV into or near protected airspace or locations. It also records the control measure taken. This entity is primarily associated with UAV command and control and related UAV transport applications. [Specification.](definitions/UAV-Event.md) | [Context example.](examples/UAV-Event-context.jsonld) | [Entity example.](examples/UAV-Event.jsonld) |
| **UAV Model** | This entity contains a harmonised description of a generic Unmanned Ariel Vehicle (UAV) model and is applicable to UAV command and control and related UAV transport applications. [Specification.](definitions/UAV-Model.md) | [Context example.](examples/UAV-Model-context.jsonld) | [Entity example.](examples/UAV-Model.jsonld) |
| **UAV State Vector** | This entity contains a harmonised description of a generic UAV State Vector, which is an Interpretation and aggregation of Automatic Dependent Surveillance–Broadcast messages. This entity is primarily associated with the control and management of Unmanned Aerial Vehicles. Each UAVStateVector instance is related to a specific UAV instance. [Specification.](definitions/UAV-State-Vector.md) | [Context example.](examples/UAV-State-Vector-context.jsonld) | [Entity example.](examples/UAV-State-Vector.jsonld) |
| **UAV TMS** | This entity contains a harmonised description of a specific Unmanned Aerial Vehicle (UAV) Traffic Management Software Application that is designed to listen to and monitor the information transmitted by UAV’s, typically this software application would be operated at a ground station. This entity is primarily associated with UAV command and control applications. [Specification.](definitions/UAV-TMS.md) | [Context example.](examples/UAV-TMS-context.jsonld) | [Entity example.](examples/UAV-TMS.jsonld) |
| **UAV UTM Flight Message** | This entity contains a harmonised description of a generic UAV UTM Flight Message, which contains a Global UTM Association protocol message. This entity is primarily associated with the control and management of Unmanned Aerial Vehicles. Each UAVUTMFlightMessage instance is related to a specific UAV instance. [Specification.](definitions/UAV-UTM-Flight-Message.md) | [Context example.](examples/UAV-UTM-Flight-Message-context.jsonld) | [Entity example.](examples/UAV-UTM-Flight-Message.jsonld) |
| **UAV UTM Flight Message Agent** | This entity contains a harmonised description of a generic UAV UTM Flight Message Agent that is designed to subscribe to the Global UTM Association protocol message according to a specific UAV entity. This entity supports the functionality of a service provider to confirm the validity of UTM Flight Message generated by UTM Flight Message Entity. The service provider can include their own Flight Control Policy to the original UTM Flight Message and forward this to a UAVTMS entity. [Specification.](definitions/UAV-UTM-Flight-Message-Agent.md) | [Context example.](examples/UAV-UTM-Flight-Message-Agent-context.jsonld) | [Entity example.](examples/UAV-UTM-Flight-Message-Agent.jsonld) |
| **Vehicle** | This entity contains a harmonised description of a Vehicle. This entity is primarily associated with the Automotive vertical segment but might also be relevant to Industry, Smart City and Agriculture related IoT applications. Where practicable https://schema.org/Vehicle naming conventions have been adopted. [Specification.](definitions/Vehicle.md) | [Context example.](examples/Vehicle-context.jsonld) | [Entity example.](examples/Vehicle.jsonld) |
| **Vehicle Fault** | This entity contains a harmonised description of a Vehicle Fault. This entity is primarily associated with the Automotive vertical segment but might also be relevant to Industry, Smart City, Agriculture and related IoT applications. [Specification.](definitions/Vehicle-Fault.md) | [Context example.](examples/Vehicle-Fault-context.jsonld) | [Entity example.](examples/Vehicle-Fault.jsonld) |
| **Vehicle Type** | This entity contains a harmonised description of a vehicleType it forms part of the description of a Vehicle. This entity is primarily associated with the Automotive vertical segment but might also be relevant to Industry, Smart City and Agriculture related IoT applications. Where practicable https://schema.org/Vehicle naming conventions have been adopted. [Specification.](definitions/Vehicle-Type.md) | [Context example.](examples/Vehicle-Type-context.jsonld) | [Entity example.](examples/Vehicle-Type.jsonld) |
| **Water Quality Observed** | This entity contains a harmonised description of the water quality at a particular location and time. This entity is primarily associated with the vertical segments of agricultural and environment and related IoT applications. [Specification.](definitions/Water-Quality-Observed.md) | [Context example.](examples/Water-Quality-Observed-context.jsonld) | [Entity example.](examples/Water-Quality-Observed.jsonld) |
| **Weather Forecast** | This entity contains a harmonised description of a Weather Forecast. This entity is primarily associated with the vertical segments of the environment and agriculture but is applicable to many different applications. [Specification.](definitions/Weather-Forecast.md) | [Context example.](examples/Weather-Forecast-context.jsonld) | [Entity example.](examples/Weather-Forecast.jsonld) |
| **Weather Observed** | This entity contains a harmonised description of the weather at a particular location and time. This entity is primarily associated with the vertical segments of the environment and agriculture but is applicable to many different applications. [Specification.](definitions/Weather-Observed.md) | [Context example.](examples/Weather-Observed-context.jsonld) | [Entity example.](examples/Weather-Observed.jsonld) |

