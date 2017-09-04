## About OpenQL Project
OpenQL (Open Quantum Libraries) is open source software for using quantum computer.
OpenQL specifications and libraries based on OpenQL is released based on Apache License 2.0 and hence free for both academic and commercial use.  
When you develop programs that operates with a quantum computer, you need tough preparation until you actually operate it.
Even if you are super-engineer with skills of traditional classical computers, it will be difficult to predict their behavior, since it is completely different from the current computer.
Therefore, as an environment to understand the operation of the quantum computer, the OpenQL project will develop a quantum computer emulator and provide an environment for engineers to learn their programming skills widely.

## Products and Services

### Quantum Computer Emulator
Quantum Computer Emulator is for dealing with pseudo quantum computers. 
The Quantum Computer Emulator (QCE) emulates the architecture that would have difference from the normal classical computer if quantum computer will realize.

During development, it is called the name of an Ukiyo-e artist (Ukiyo-e is traditional Japanese Art) as its code name. 
Depending on its use, we will provide you with upgrading as follows. 

*Hokusai* (Version 0.x, beta release)  

Hokusai has a mechanism for handling basic circuits of quantum computers.
The behavior of qubits in quantum computers requires knowledge quite different from conventional classical computers.
Hokusai aims to learn the behavior of this qubit.  

Hokusai’s specification is:

+ A quantum operator for handling quantum bits of a quantum computer works.
+ List of handled quantum operators are the bellow.  
  Identity operation（I）,  
  Bit inversion operation（X）,  
  Phase inversion operation（Z）,  
  Phase bit inversion operation（Y）,  
  Hadamard operation（H）,  
  pi/2 phase shift operation（S）,  
  -pi/2 phase shift operation（S†）,  
  pi/4 phase shift operation（T）,  
  -pi/4 phase shift operation（T†）,  
  CNOT gate operation（~C~）,  
  Observation operator（M）  

+ Hokusai QPU Emulator is an emulator of 8-bit QPU that provides one Quantum Register.
+ Hokusai’s web interface provides two operating mode; that is a designing mode and an interaction Mode.
+ On the designing mode, you can drag and drop quantum operator icons shown in Control-View to QPU-View, and connect each icons.
+ On the interaction mode, you can run the quantum emulator, and can see its result in Result-View or Bloch-Sphere-View.

## Activities

+ Providing the Docker for using Quantum Computing Emulator.
+ Developing OpenQL programming language specification.
+ Researching Quantum Computing Algorithm.
+ Developing Application using OpenQL.
