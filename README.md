
**What is IoT Plug and Play?**  
:::image type="content" source="pic/1.png" alt-text="pnp":::  

While developing a cloud-based IoT solution has never been faster or more secure, we’re always looking for ways to make it easier. IoT is crossing the technology adoption lifecycle chasm by moving from early adoption to mainstream use. Those in the mainstream phase need easy-to-use solutions that provide rapid time to value. 
 

One of the major challenges when developing an IoT solution is the tight coupling between the software on the device and the cloud solution. Integration of devices into cloud solutions is time consuming and slows down the development and scaling of cloud solutions. IoT Plug and Play solves this challenge by providing a schema for IoT interaction. The interaction is a model between IoT physical devices and the cloud solutions to which they connect.    
 
:::image type="content" source="pic/2.jpg" alt-text="2":::    

 
 
IoT Plug and Play simplifies device interactions in IoT solutions with an open modeling language. At the core of IoT Plug and Play is a device model used to advertise a device’s capabilities to an IoT Plug and Play-enabled application. This model enables device builders to build devices that can be easily integrated to cloud-based IoT solutions and IoT services such as: Azure IoT Central, Azure Digital Twins, and third-party solutions built by solution partners. 

For example, IoT Plug and Play and Azure Digital Twins use the same schema for modeling; as a result, IoT Plug and Play devices becomes a node in the digital twin knowledge graph. Once IoT Plug and Play is enabled by solution builders, solutions can understand devices’ capabilities and   interpret data sent from the devices by referencing device models from the model repository. This allows solutions to “play” or interact with the devices without any code changes.

Azure IoT platform updates and releases for IoT Plug and Play
Azure IoT platform services, such as Azure IoT Hub and Device Provisioning Service, are updated to support IoT Plug and Play. Now, you can incorporate IoT Plug and Play devices into Azure IoT Hub-based solutions and the platform services will recognize IoT Plug and Play capabilities.  
Summary of updates and releases:
•	IoT Plug and Play is now enabled and deployed in all Azure regions
•	Support for Digital Twin Definition Language (DTDL) version 2
•	Azure IoT Explorer
•	Azure IoT extension for Azure CLI
•	Visual Studio and Visual Studio Code extensions
•	Digital Twin Definition Language Model Parser
•	IoT Plug and Play Bridge
•	Device Model Repository

Software development kits (SDKs)
Both device SDKs and service SDKs are updated to support IoT Plug and Play device and solution development. Embedded C and Azure RTOS middleware SDKs are added to the device SDK family.  

Please find links to each SDK at Microsoft Azure IoT SDKs
Device SDKs for device builders	Service SDKs for solution builders
•	.NET
•	Java
•	Node.JS
•	Python
•	C
•	Embedded C
•	Azure RTOS middleware
•	.NET
•	Java
•	Node.JS
•	Python
Samples and Documentations
Each SDK is updated with sample code and associated documentation to get started. View IoT Plug and Play documentation, as well as SDK samples, reference documents, and Quickstart guides.

Developer tools
We have also released new tools to support developers with enabling IoT Plug and Play devices and solutions.

•	Visual Studio and Visual Studio Code extensions
Support DTDL v2 model authoring with Intellisense.
•	DTDL Parser Library
Check and validate DTDL v2 compliance.
•	Azure IoT Explorer
Visualize the device model announced by IoT devices and interact with devices. 
•	AZ CLI Extension
Command line tool to validate IoT Plug and Play compliance.
•	IoT Plug and Play Bridge
Open source software to allow existing devices to act as IoT Plug and Play device.
Developer Reference
•	Digital Twin Definition Language (DTDL) version 2 
•	Developer Guide: IoT Plug and Play architecture

Azure Certified Device: IoT Plug and Play certification
As part of the Azure Certified Device program, IoT Plug and Play certification is now ready for new device submissions. Certified devices can be published to the Azure Certified Device Catalog, which helps promote your devices to a global community. Please visit Getting Started with the Azure Certified Device program to learn more about certifying your devices for IoT Plug and Play.

•	How to certify IoT Plug and Play devices
•	IoT Plug and Play certification requirements
•	Azure Certified Device program FAQ
Azure Certified Device submission portal
Please visit the submission portal to start certifying your device. The submission portal runs automated validation test to ensure your device is compliant with IoT Plug and Play convention and DTDL v2.
Azure Certified Device Catalog
The Azure Certified Device Catalog is an online marketplace for device builders to showcase their IoT Plug and Play-certified devices.  We have taken feedbacks from partners and introducing a renewed catalog site with improved search to provide one-stop-shop for buyers.	 

Additional Resources
•	Getting Started with the Azure Certified Device program 
•	Azure Certified Device program FAQ 
•	Azure Certified Device submission portal





