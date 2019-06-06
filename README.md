# projecttree
circle 프로젝트에 사용하기 위해서 고안중이 폴더구조이다.

## Rules
- 버전관리는 AWS s3 의 버킷 버전관리를 사용한다.
- 라이팅, 렌더링을 블렌더 내부에서 한번에 진행한다.

## Concept
- 시퀀스 파일은 한 폴더안에서 동일한 확장자만 존재하는 것이 좋다.
- 프록시 데이터는 언제든지 삭제할 수 있도록 완전히 주요 경로에서 분리한다.
- 게임 프로젝트라면 언리얼엔진 구조를 사용한다.

## Reference
- Bam : https://docs.blender.org/manual/en/latest/pipeline/bam.html