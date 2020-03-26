# REFrameworkAnalysis

### REFramework 만들어보기

1. Main 
- StateMachine으로 만들어져있으며 각각의 transition 상태에 따라 연결이 되어있음

2. Init State(Initialization)
- config 파일에 대한 설정 저장 
  - Config 파일이 있을경우 InitAllSettings에서 값을 설정한다. 
  - Data\config 파일에서 값을 가져와 whitespace를 제거하고 
  - Config파일에서 불러온 테이블 row를 각각 Dictionary 형태의 Name(key)과 대한 Value(Value)를 저장한다.
  - Config에서 Asset 이름 받아서 Orchestrator의 asset값 찾고, out_Config 에 AssetValue(generic type)를 저장한다.
  - Config에 OrchestratorQueueName이 있는 경우 out_Config에 QueueName 설정
  
  
  
  
  
  
