Is there anyone experienced who could try running this operating-system-like project? I can provide the .md file, but I’m not getting it to work properly on my end.


Could anyone help refine my prompt? I can provide the Markdown (.md) document, and I can run it again afterward. Collaboration is also welcome.


This may be an unusual request, but I believe it could serve as a meaningful benchmark for what AI-assisted software engineering is truly capable of today.

Has anyone successfully used AI to build software that tightly integrates hardware-human social networking with an operating-system-level architecture—for example, something similar to GPT-5.6?

I’m asking because I’ve seen many recent discussions suggesting that AI can now generate complete software projects end-to-end within a single workflow. For more complex systems, AI-driven autonomous development (through prompting, tool loops, or agent-based workflows) is reportedly capable of completing over 70% of engineering tasks autonomously, including internal workflows at companies like Anthropic and OpenAI.

With that in mind, I’d like to ask whether anyone here would be interested in helping build the project described below.

I'm open to any implementation approach—pure prompt engineering, iterative loop-based agents, or any hybrid workflow—as long as it can move the project forward in a meaningful way.

Even partial contributions would be highly valuable. For example, implementing one or more critical subsystems—such as the domain architecture or the consensus mechanism—would already represent major progress.

You can treat the following project description as a Markdown specification, potentially including prompts and implementation guidance.

</> Markdown

#### Introduction

- This Markdown document is intended to be used by the latest large language models (or coordinated multi-model systems) to generate a next-generation operating system.
- Requirement: If current-generation models are not yet capable of fully realizing this system, development may wait for the next generation of models, and continue iteratively until completion becomes possible.
- Mission and significance: To support humanity's expansion beyond Earth and enable true connectivity among all things.

For a long time, the Internet has drifted away from its original purpose. Fragmentation, platform silos, and information isolation have made frictionless access to knowledge and capability increasingly unrealistic. The ideal of invoking and orchestrating all things from a single endpoint cannot be realized through today's Internet. To move beyond its limitations, we must look beyond Earth. Space exploration presents such an opportunity. As information generated across celestial bodies reaches an unprecedented scale, today's Earth-centric Internet will inevitably be subsumed into this new networking architecture. The data accumulated on Earth will become only a small component of a much larger interplanetary information ecosystem.

#### Software Architecture

Core Direction：

1. This is an operating system designed to enable the Internet of Everything, establishing functional equality between humans and objects.
2. This is a space-scale operating system designed to maintain seamless information connectivity across planets, moons, space habitats, and other celestial bodies.
3. It is minimalistic, open-source, and designed for the most direct and frictionless possible flow of information.


Framework：

1. Frontend — The “Mindflow” Intelligence Layer
- The frontend operates within an intelligent layer called Mindflow. Every interaction interface is dynamically predicted, generated, and rendered by AI in real time for human users. (The emphasis here is on humans, not objects)、(Mindflow functions as a unified AGI council—an orchestration layer connecting multiple large models. It operates like an “AI parliament,” where different intelligence systems deliberate, specialize, and coordinate to make decisions and provide services for humanity)

2. Foundation Layer — Contracts and Consensus
The foundational layer operates through proposal formation and contract execution. Email-like communication acts as the immutable evidence layer for recordkeeping. Once relationships between entities are established and locked, they become the basis of consensus. Every transaction, interaction, or agreement is individually verified and cryptographically stamped.

3. System Layer — Grounded Consensus Network
The system runs on a consensus information network whose primary grounding reference is Earth (the home planet). Earth serves as the initial grounding node of trust and synchronization. From this foundation, the network can expand infinitely while maintaining “grounded” data integrity. This creates a scalable consensus architecture capable of extending from Earth to interplanetary civilization.


#### Representative Scenarios (Ordered from Simple to Advanced)

- The following examples are intended to help AI agents understand the intended architecture and interaction model. They progress from simple device interactions to planetary-scale coordination.

1. Universal Addressing

Every entity—human, device, service, organization, or celestial body—is assigned a unique mail address. Cross-domain communication is performed through these addresses. Humans and objects are treated as equal participants at the application layer while remaining isolated by clearly defined permission boundaries. Devices may optionally use hash-based email addresses as their underlying identities.

2. Device Communication Through Mail

A user sends a message to a light:
Turn on the light.

The light executes the request and replies:
The light has been turned on.

A washing machine sends its configuration dashboard to the user.
After configuration, the user replies.

The house routes the message to the washing machine, which further distributes the task to its internal functional modules through its internal message bus.

The general workflow is: Device joins the network → receives an address → user communicates through mail → internal modules receive distributed messages → execution completes → confirmation is returned.

3. Plug-and-Play Devices

When a device joins the network:

it receives a permanent address,
its identity is confirmed through consensus,
it automatically contacts the manufacturer's mailbox,
downloads the appropriate driver package,
installs required software,
upgrades firmware,
and becomes immediately operational.

No manual driver installation should ever be required.

Example:

A printer connects to the system.

Instead of asking the user to install drivers, it authenticates with the manufacturer and automatically retrieves the appropriate software package.

4. Intelligent Document Processing

A user sends a document to a printer. The printer automatically determines the printable content from the message body or its attachments.

After printing finishes, it sends a confirmation message: Printing completed successfully.

5. Social Interaction Between Humans and Devices

A user may communicate simultaneously with many devices through their mailboxes. Devices can be organized into conversation groups. Users may:

assign tasks,
deploy services,
configure devices,
or even program devices through messages.

Every device maintains a trusted communication channel with its manufacturer. If a fault occurs, the device communicates directly with the manufacturer for diagnosis and repair whenever possible.

6. House-Level Workflow Automation

Before the owner arrives home, the house receives a message.

The house decomposes the request into multiple subtasks and distributes them to lighting, climate control, security, entertainment, kitchen appliances, and other systems.

When the owner arrives, all devices have already completed their startup sequence according to the desired workflow.

7. Enterprise Workflow

A company receives an email containing a contract. The operating system automatically:

identifies individual clauses,
routes each section to the responsible department,
collects revisions,
reconstructs the complete document,
records consensus,
and returns the finalized contract.

Purchase orders follow the same principle. Tasks may be routed to manufacturers, organizations, AI agents, or human specialists.

8. Autonomous Collaboration

Manufacturers periodically send firmware updates to devices.

Devices automatically install compatible updates.
Devices also negotiate tasks directly with one another.
After collaborative work is completed, the participating devices notify the owner.

9. Component-Level Addressability

Every component inside a vehicle has its own address. Every manufacturing event, maintenance record, and operational log is traceable through message history.

The vehicle's internal mail-communication bus functions as an internal conversation network. Collected information is continuously summarized into a real-time dashboard for the user.

10. Dynamic User Interfaces

No fixed graphical interface exists. Interfaces are generated on demand through AI. Every entity can expose different interfaces according to permission levels. Messages are automatically divided into:

public information,
protected information,
administrator-only information.

Humans similarly separate social content into public and private views.Devices expose operational dashboards while protecting sensitive controls.

11. Planetary Monitoring

Sensors deployed on celestial bodies continuously report environmental conditions and system status. These reports are delivered to owners and manufacturers. Authorized users may monitor or control the systems.

Unauthorized users may still access publicly available telemetry through address-based browsers and submit recommendations. No dedicated application is required.

12. Planetary Communication

Humans communicate directly with the Moon. Example: > Illuminate the entire lunar surface. or > Display a smiling face using lunar lighting infrastructure. Planets communicate directly with one another. Example: Mars requests temporary storage resources from Earth.

The planets jointly publish a public system announcement. The Hubble Space Telescope automatically replies: > Camera ready. Awaiting observation.

13. Solar-System-Scale Coordination

The entire Solar System behaves like a distributed intelligent organism. It continuously monitors environmental conditions, predicts hazards, coordinates defensive actions against threats such as asteroids, and mobilizes available infrastructure to protect life.

Collective human objectives become executable workflows spanning planets. To preserve trust and consistency, every communication path ultimately references Earth as the grounding node of the consensus network.

14. Universal Social Networking

Humans communicate with objects. Objects communicate with objects. Objects negotiate contracts, exchange services, perform settlements, allocate resources, and cooperate autonomously. Human-to-human communication follows the same underlying protocol.

15. Proposal–Contract–Consensus

Every interaction—whether between humans, machines, organizations, or celestial bodies—is represented as: Proposal → Agreement → Execution → Verification → Consensus Record. Every workflow is cryptographically stamped.

Promises become verifiable commitments rather than informal agreements.

16. Knowledge Engine

The operating system continuously delivers the most useful knowledge and capabilities to both humans and machines. Knowledge ranking is determined by usefulness, correctness, and long-term value rather than commercial incentives or popularity.

Every contributor—human or machine—is rewarded whenever their knowledge is reused, allowing the ecosystem to improve continuously over time.

......

#### Why choose an email-based communication protocol as the foundation of extreme minimalism?

Reasons:

1. It is a system that is inherently capable of cross-domain operation.  
   Common understanding (a): Email is the first application of the Internet, and its usage patterns and cognitive foundation are already deeply established.  
   Common understanding (b): The cross-domain nature of email addresses makes it low-cost to bridge heterogeneous systems, enabling interoperability between legacy systems and new architectures through email-based communication.

2. The structure of email addresses is naturally clean, uniform, and semantically domain-oriented. Humans are already familiar with it, and it has a very low cognitive entry cost.  
   In this context, it is suggested that it may be time to assign domains to planets.  
   Fast communication can be handled via real-time messaging, while slower interplanetary data exchange aligns naturally with the classical human experience of “sending and receiving letters,” achieving a design principle of extreme simplicity.

3. Software is email.  
   Reading a description or accessing a service is equivalent to contacting its email address.  
   Requesting functionality is done simply by sending a message.  
   Collaboration is achieved via forwarding. After execution, results are archived and returned via reply messages.  
   Functional composition is driven by AI agents that route 'mailto' requests to target entities, dynamically attaching required skills as payload packages, and returning results through a topology-based 'topia' response channel.

4. Everything has value, and value dynamically changes based on consensus formed around events.  
   Using the Ship of Theseus as an example: consensus shifts as components are replaced; value migrates as old parts form new structures. Both “ships” evolve under changing collective agreement, and no logical paradox remains under a consensus-based interpretation.

5. The physical world exhibits a highly structured and well-defined informational logic.  
   The amount of information generated by fully interconnected objects can exceed human digital social systems by several orders of magnitude, and logs are inherently more structured and precise.  
   Beyond consensus constraints, humans should define strict boundaries based on the semantics of mail addresses and establish cognitive red lines early in the system design.

6. Traditional email systems still contain security and completeness limitations.  
   The redesigned system, **MAILTOPIA**, can fully address these shortcomings and provide a more robust bridge between Earth and extraterrestrial systems.

7. The current trend in cross-platform technology relies heavily on AI-based fuzzy mediation, which introduces multiple intermediate layers and reduces efficiency.  
   A direct email-based addressing system allows AI to focus on knowledge integration and task execution, rather than acting as a fragile glue layer between systems.


#### Why build such an operating system

Limitations of the current Internet:

1. Humanity will not remain confined to Earth indefinitely. It is difficult to imagine that the current fragmented Internet—full of patches, layers of abstraction, and inefficiencies—can be extended and sustainably operated across other planets.

2. As humans continue to push deeper into the underlying layers of the Internet, attempting to route instructions through increasingly short and direct paths to agents, a fundamental question arises:  
   rather than continuously optimizing and patching the existing network, why not rebuild the system from the ground up?  
   A completely new networking paradigm may ultimately be more cost-efficient and scalable.


#### It is an essential and critical tool for celestial exploration:

1. Celestial exploration and development is a large-scale collaborative effort across humanity, requiring a unified and seamless information and data operating model as its foundation.

2. During the process of constructing and developing extraterrestrial infrastructure, disputes over ownership are inevitable. Establishing clear and immutable ownership definitions, as well as incentive mechanisms, requires a global consensus across all of humanity.

3. Constraints on artificial intelligence must be grounded in human consensus as the highest-level authority, in order to intervene in, balance, and mitigate undesirable early-stage tendencies.

Others:

1. Detailed documentation regarding human-object social interaction models and interfaces can be provided upon request.
   https://github.com/mailtopia/mailtopia/raw/refs/heads/main/Bit%20Object.doc

2. Detailed documentation regarding the consensus system for defining and partitioning the value ownership of digital-physical entities can be provided upon request.
   https://github.com/mailtopia/mailtopia/raw/refs/heads/main/MAILTOPIA.zip


航天观点，以月球为举例（勿要用地球观点看待月球的建设）： 人类的第一个永久驻扎点最应该的方式是在月空而不是在月表，运行的是在可变动的机动轨道上，因此对探索成果的共识是资产而非土地

月面驻扎评价：

人类不可能也没那么多资源在短期内驻满月表
月球永昼区域面积十分有限，局限于狭小空间的竞争完全没意义
月球着陆技术难度高、风险大、起降成本高
月面基地建设周期长、耗费高、人员往来不便利
固定驻扎具有月震与陨石风险、月尘问题造成巨大麻烦
原位资源的采集、加工制造难以即刻成熟
月表宇宙射线辐射大，人员需要躲避月球隧洞居住
月表极其单调，生活措施简陋，对人类心理生理健康造成巨大破坏
月空驻扎评价：

椭圆轨道具有较长时间的光照期，近月点快速移动耗时短，夜期极短
克服质量瘤，绕月舱以极小能量支持即可长期稳定运行
航天器可提前实现预警，机动灵活地变轨以躲避陨石
抗宇宙射线效果等同月球隧洞，生活措施较完善、人员转换便利
同样可以承担月空工厂、太空计算、核动力设施的安置
转运输耗费小、效率高，原因 https://github.com/ReadClaw/ReadClaw
往月空投送资产建立共识信息网理由：

月球亲铁元素极为匮乏，地球火箭体完全没有必要进行大规模可回收重复使用，完全可以作为未来的元素资产存储于月空近月轨道处
月球近月轨道航天器可以部署计算资源，成为月端计算，服务月球建设和供应地球；随着月球舱增加，可以建设为月空的集群城市
在月表真空中试验与完善高精度高空投放技术，以气囊包裹-绵湖-坑基气囊实现物资的软着陆与溅落
月球早期探索主角既非人类也非机器，而是传感器；需要把传感器大面积播散，形成共识的通讯与探测基础，而后才让机器运行其间
把月球作为大型开发开放平台，以开源模式让公众参与，以共识的激励机制把成果和经验快速复制到其它星球

```
