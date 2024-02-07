# Gateway Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-GDA-* issues (requirements) listed at [PIOT-INF-02-001 - Lab Module 02](https://github.com/orgs/programming-the-iot/projects/1#column-9974938).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

1. What does your implementation do? 

The implementation will deal with setting up capability for records management, analytics, and configuration control inside the GDA. ⁤
The purpose is to ensure that information flows seamlessly between the CDA and cloud services, resulting in efficient statistics processing, garage, and evaluation. ⁤ ⁤
The GDA will create verbal exchange channels between the CDA and cloud offerings to facilitate statistics interchange and processing. ⁤ ⁤
The GDA will keep data locally as needed, interpret incoming telemetry statistics, and make choices based on predefined criteria or configurations. ⁤ 
The GDA will simplify the transport of instructions to the CDA for actuation. 
The GDA will run preliminary analytics on the received information to generate insights for decision-making.
GDA will create a significant middle link between CDA methamphetamine level and cloud solutions with data streaming laminating in a neutral IOT platform, so as to bridge the gap seen among these features.

2. How does your implementation work?

It creates paths for data to flow among the GDA, CDA, and cloud services. This lets data transfer and processing happen smoothly.
Keeps track of data locally when needed and takes care of incoming data signals.
Makes decisions based on set limits or rules to start certain actions.
Allows for sending instructions to the CDA for it to carry out these actions.
It first does quick checks on data to help in choosing what to do next.
Joins the edge tier (CDA) and cloud services to make sure data moves freely and IoT tasks are run efficiently.
This way, the GDA handles data, analytics, and settings in the IoT world. It links edge tier and cloud services smoothly.

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

Master URL: https://github.com/ENGR5520W24/assign-1-iot-gda-gp-7

Branch URL: https://github.com/ENGR5520W24/assign-1-iot-gda-gp-7/tree/labmodule02

### UML Design Diagram(s)

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).

<img width="628" alt="labmodule02" src="https://github.com/ENGR5520W24/assign-1-iot-gda-gp-7/assets/86999539/1d4e22af-4867-4dfc-bbb5-129e307cbab1">


### Unit Tests Executed

NOTE: TA's will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- **ConfigUtilTest** :  The functionality of the configuration utility component within the Gateway Device Application is probably the primary focus of this unit test. Testing different aspects could be a part of it.

![WhatsApp Image 2024-02-07 at 1 28 19 PM](https://github.com/programming-the-iot/book-exercise-docs/assets/86999539/a2358ffd-a852-42e9-80ee-268b7c14fc88)

- **SystemCpuUtilTaskTest**: The functionality of the CPU utilization monitoring task within the Gateway Device Application is most likely the main focus of this unit test.

<img width="868" alt="Screenshot 2024-02-07 at 1 30 59 PM" src="https://github.com/programming-the-iot/book-exercise-docs/assets/86999539/a9e98cf2-b199-481e-a8f1-ee85ccb8a076">

- **SystemMemUtilTaskTest**: This unit test certainly focuses on evaluating the Gateway Device Application's memory utilization monitoring task's functioning.

![WhatsApp Image 2024-02-07 at 1 29 53 PM](https://github.com/programming-the-iot/book-exercise-docs/assets/86999539/9cd34f1a-774f-4f1b-be3a-ecc85b6671af)

### Integration Tests Executed

NOTE: TA's will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- **GatewayDeviceAppTest**: By evaluating the integration of its several modules or components, this integration test most likely aims to evaluate the Gateway Device Application's overall operation and behavior.

<img width="1151" alt="Screenshot 2024-02-07 at 1 25 50 PM" src="https://github.com/programming-the-iot/book-exercise-docs/assets/86999539/a14bcbb1-10f5-4fdd-aa7c-8f677509467d">

- **SystemPerformanceManagerTest**: The primary goal of this integration test is to verify the behavior and functionality of the Gateway Device Application's System Performance Manager module.

<img width="1197" alt="Screenshot 2024-02-07 at 1 27 05 PM" src="https://github.com/programming-the-iot/book-exercise-docs/assets/86999539/8fe8fb20-cb90-4644-bd93-7be0c11a807b">

- **Connect SystemCpuUtilTask and SystemMemUtilTask to SystemPerformanceManager**:

  ![WhatsApp Image 2024-02-07 at 1 30 24 PM](https://github.com/programming-the-iot/book-exercise-docs/assets/86999539/e5b964bf-ca12-4de2-8afa-0eea18b3a077)



EOF.
