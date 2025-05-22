Update time: March 19, 2024






```
.
├── bin  Storage location for generated executable files
├── cmake-build-debug  Project compilation directory, not included by default, needs to be created
├── docs  Storage location for project documentation
│   └── images  Storage location for project documentation images
├── example  Storage location for example code
│   ├── fiberExample  Coroutine-related code
│   ├── raftCoreExample  Raft core code
│   └── rpcExample  RPC-related code
├── lib  Storage location for compiled library files
├── src  [IMPORTANT] Storage location for project source code, organized by sub-modules
│   ├── common  Shared by sub-modules, generally includes utilities, logging, configuration files
│   ├── fiber  Coroutine-related code
│   ├── raftClerk  Raft client code
│   ├── raftCore  Raft core code
│   ├── raftRpcPro  Protoc files involved in Raft RPC
│   ├── rpc  RPC library-related code
│   └── skipList  Skip list (upper-level state machine) related code
└── test  Storage location for test code, not very significant, generally used to test uncertain features
```







