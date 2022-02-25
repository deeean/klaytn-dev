# state-migration

클레이튼 엔드포인트 노드 스토리지를 절약하기위해 State Migration을 진행하고 내용을 기록합니다.

# Documentation
- [medium](https://medium.com/klaytn/klaytn-v1-5-0-state-migration-%EB%85%B8%EB%93%9C-%EC%8A%A4%ED%86%A0%EB%A6%AC%EC%A7%80-%EC%A0%88%EC%95%BD%ED%95%98%EA%B8%B0-358dd77d9fd6)

# Reports
> 주의: EKS 환경에서 테스트하였습니다.

cypress기준 m5.4xlarge 에서 메모리가 부족하여 evicted 됩니다. (peak 63.2GB)

m5.8xlarge를 사용해야합니다.

또 블럭 동기화가 느려지는 경우가 발생합니다. 최대 1500블럭까지 차이가 나는 경우도 있습니다.