# 7zr

> 높은 파일압축률을 보여주는 압축 프로그램.
> .7z파일들만을 지원하는 `7z`의 독립형 버전.
> 더 많은 정보: <https://manned.org/7zr>.

- 파일이나 디렉토리 압축하기:

`7zr a {{경로/archived.7z}} {{경로/파일명_또는_디렉토리명}}`

- 압축파일 암호화 (including file names):

`7zr a {{경로/encrypted.7z}} -p{{비밀번호}} -mhe={{on}} {{경로/archive.7z}}`

- 기존 디렉토리 경로에 존재하는 7z파일 추출하기:

`7zr x {{archived.7z}}`

- 특정 디렉토리에 압축파일 추출:

`7zr x {{경로/archive.7z}} -o{{아웃풋/의/경로}}`

- `stdout`에 압축파일 추출:

`7zr x {{경로/archive.7z}} -so`

- 압축 파일의 내용 리스트:

`7zr l {{경로/archived.7z}}`

- 압축 수준을 설정 (수준이 높을수록 압축률이 높아지지만, 속도는 느려짐):

`7zr a {{경로/대상/아카이브.7z}} -mx={{0|1|3|5|7|9}} {{경로/대상/파일_또는_디렉터리}}`
