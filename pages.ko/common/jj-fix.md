# jj fix

> 형식 수정 또는 기타 내용 변환을 통해 파일을 업데이트.
> 리비전은 이후 `jj op show -p`로 검토 가능.
> 더 많은 정보: <https://docs.jj-vcs.dev/latest/cli-reference/#jj-fix>.

- 작업 복사본 커밋에 연결된 모든 변경 가능 리비전의 변경된 파일 수정:

`jj fix`

- 지정한 리비전과 그 하위 리비전의 변경된 파일 수정:

`jj fix {{[-s|--source]}} {{revsets}}`

- 작업 복사본 커밋의 파일만 수정:

`jj fix {{[-s|--source]}} @`

- 특정 파일이나 디렉터리만 수정:

`jj fix {{경로/대상/파일_또는_디렉터리}}`

- 수정된 줄만이 아닌 모든 줄 수정:

`jj fix {{[-a|--all-lines]}}`

- 특정 파일의 모든 줄 형식 지정:

`jj fix {{[-a|--all-lines]}} {{경로/대상/파일}}`

- 전체 저장소에서 변경된 파일뿐 아니라 변경되지 않은 파일도 수정:

`jj fix --include-unchanged-files`

- 특정 경로에 대해 변경된 파일뿐 아니라 변경되지 않은 파일도 수정:

`jj fix --include-unchanged-files {{경로/대상/파일_또는_디렉터리}}`
