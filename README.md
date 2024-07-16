# vector
Build data pipeline with Vector

## Step 1
### Application log 파일을 source로 사용하여 console에 출력하는 pipeline
[ISSUE-1](https://github.com/BEDongryeol/vector/blob/01728d2b3a6bae35bb4d1f96ae1a195b5e29e7c9/step1/vector.yaml)
  - [Resolved](https://github.com/BEDongryeol/vector/commit/768a118804abf645283b1bd90142201188ae58dc)logging pattern에 따른 field 매핑 실패
  - file은 바로 입력되지만 sink에서 즉시 출력되지 않음
 


# Appendix
## DOCS
### Configuration
[Sources - file](https://vector.dev/docs/reference/configuration/sources/file/)

## REF
[TossTech - 대규모 로그 처리](https://toss.tech/article/slash23-data)

[Multi CDN 로그 및 트래픽 관리](https://techblog.lycorp.co.jp/ko/managing-multi-cdn-logs-traffics-with-vector)
