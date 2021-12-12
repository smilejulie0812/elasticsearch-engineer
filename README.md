# Elasticsearch Engineer 가 되는 길
2017년 겨울, 회의록을 작성하면서 エラスティックサーチ 라느니 ログスタッチュ 라느니 キバナ 라느니 하는 용어를 처음으로 접했고  
그 다음 해가 넘어가자마자 참가한 장기 프로젝트가 바로 ELK Stack 으로 SIEM 을 구성하는 것이었다.  
(당시에는 Elastic SIEM 서비스가 존재하지 않아서 직접 구축했다)  

아주 처음 Logtash pipeline 으로 고객사의 온갖 로그를 파싱하던 일로 머리를 싸매던 신참내기 시스템 엔지니어는 어느 새 Elasticsearch 담당자로 여러 업무를 담당하고 있다.  
다만 과연 내가 어디까지 이 Elastic Stack 을 알고 있는지, 손에 익은대로 작업은 할 수 있지만 말로 유창하게 설명할 수 있을 정도로 지식이 정돈되어 있는지 감이 잡히지 않는다.

https://www.elastic.co/kr/training/elastic-certified-engineer-exam  
마침 Elastic Certified Engineer 자격증이 있어 도전하고 싶었으나...  
선행 수업으로 Elasticsearch Engineer 라는 나흘 짜리 수업을 들어야 하는데 이 수업이 무려 2400 달러(...) 가난한 엔지니어는 감히 도전해 볼 수가 없고...  
그리하여 결심했다! 자격증이고 수업이고 우선은 내가 한 번 정리해 본다!  
Elastic Stack 지식도 정리해 보고, 겸사겸사 영어 공부도 해 볼 기회로 만들어 보자.

# 개정판
최근 개정된 강의 목차가 아래와 같다.  
각각의 디렉토리를 생성, readme 파일에 설명과 알맞은 내용을 추가하여 적도록 한다.  
https://www.elastic.co/kr/training/elasticsearch-engineer
* Data Modeling
* Data Management
* Data Processing
* Cluster Management
* Developing Search Applications
* Shards
  
아래는 개정 전의 강의로, 2 파트로 나뉘어져 있었던 것 같다.  
아래 목차를 위의 개정판에 알맞게 분배하여 빠지는 내용 없이 녹여서 학습하도록 한다.
## Elastic Engineer 1
https://www.elastic.co/kr/training/elasticsearch-engineer-1
* Elastic Stack Overview
* Getting Started with Elasticsearch
* Querying Data
* Text Analysis and Mappings
* The Distributed Model
* Troubleshooting Elasticsearch
* Improving Search Results
* Aggregating Data
* Securing Elasticsearch
* Best Practices

## Elastic Engineer 2
https://www.elastic.co/kr/training/elasticsearch-engineer-2
* Field Modeling
* Fixing Data
* Advanced Search and Aggregations
* Cluster Management
* Capacity Planning
* Elasticsearch Internals
* Document Modeling
* Monitoring and Alerting
* Moving from Dev to Production
