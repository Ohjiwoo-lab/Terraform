# AWS Architecture by Terraform

[배워서 바로 쓰는 14가지 AWS 구축 패턴](https://www.yes24.com/Product/Goods/88240901) 책에서 다루는 아키텍처를 직접 Terraform으로 구축해보려고 합니다.

**왜 Terraform인가요?**

콘솔을 통해 일일히 생성하는 방법도 있지만, 관리하기가 힘들다는 단점이 있습니다. 어떤 리소스를 무슨 목적으로 생성했는 지를 알지 못하기 때문에 생성해두고 사용하지 않고 방치되기도 합니다. 그래서 코드로 인프라를 관리하면 만들었다가 한 번에 삭제하기도 유용하다는 생각이 들어서 IaC를 사용해보고자 생각했습니다.

그 중에서도 Terraform을 선택한 이유는 오픈소스이기 때문에 커뮤니티가 활발해서 정보를 얻기 쉽다는 점과, 코드가 간단하고 직관적이어서 빠르게 학습할 수 있을 것 같았기 때문입니다.
