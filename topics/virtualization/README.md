## Virtualization

<details>
<summary>What is Virtualization?</summary><br><b>

Virtualization uses software to create an abstraction layer over computer hardware that allows the hardware elements of a single computer—processors, memory, storage and more - to be divided into multiple virtual computers, commonly called virtual machines (VMs).
</b></details>

<details>
<summary>What is a hypervisor?</summary><br><b>

Red Hat: "A hypervisor is software that creates and runs virtual machines (VMs). A hypervisor, sometimes called a virtual machine monitor (VMM), isolates the hypervisor operating system and resources from the virtual machines and enables the creation and management of those VMs."

Read more [here](https://www.redhat.com/en/topics/virtualization/what-is-a-hypervisor)
</b></details>

<details>
<summary>What types of hypervisors are there?</summary><br><b>

#### Type 1 Hypervisors, also known as bare-metal or native

Provides excellent performance and stability since it doesn't run inside Windows or any other OS.

- This Hypervisor's Pros
  - VM Mobility, Security and Resource Over-Allocation.
- This Hypervisor's Cons
  - Limited Functionality, Complicated Management and Price.
- Type 1 Examples
  - VMware vSphere with ESX/ESXi / KVM / Microsoft Hyper-V / XenServer

#### Type 2 Hypervisors, also known as hosted hypervisors

- This Hypervisor's Pros
  - Easy to manage, Convenient for testing and Allows access to additional productivity tools
- This Hypervisor's Cons
  - Less flexible resource management, performance and security
- Type 2 Examples
  - VirtualBox / VMWare Workstation

Read more [here](https://phoenixnap.com/kb/what-is-hypervisor-type-1-2)

</b></details>

<details>
<summary>What are the advantages and disadvantges of bare-metal hypervisor over a hosted hypervisor?</summary><br><b>

Due to having its own drivers and a direct access to hardware components, a baremetal hypervisor will often have better performances along with stability and scalability.

On the other hand, there will probably be some limitation regarding loading (any) drivers so a hosted hypervisor will usually benefit from having a better hardware compatibility.
</b></details>

<details>
<summary>What types of virtualization are there?</summary><br><b>

Operating system virtualization
Network functions virtualization
Desktop virtualization
</b></details>

<details>
<summary>Is containerization is a type of Virtualization?</summary><br><b>

Yes, it's a operating-system-level virtualization, where the kernel is shared and allows to use multiple isolated user-spaces instances.
</b></details>

<details>
<summary>How the introduction of virtual machines changed the industry and the way applications were deployed?</summary><br><b>

The introduction of virtual machines allowed companies to deploy multiple business applications on the same hardware while each application is separated from each other in secured way, where each is running on its own separate operating system.
</b></details>

#### Virtual Machines

<details>
<summary>Do we need virtual machines in the age of containers? Are they still relevant?</summary><br><b>
</b></details>
