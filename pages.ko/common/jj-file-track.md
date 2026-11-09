# jj file track

> `jj` 저장소의 작업 복사본에서 지정한 경로 추적 시작.
> 관련 항목: `jj file untrack`.
> 더 많은 정보: <https://docs.jj-vcs.dev/latest/cli-reference/#jj-file-track>.

- 작업 복사본의 추적되지 않는 모든 파일 추적:

`jj file track`

- 특정 파일이나 디렉터리 추적:

`jj file track {{경로/대상/파일_또는_디렉터리}}`

- 여러 경로 추적:

`jj file track {{경로/대상/파일1 경로/대상/디렉터리2 ...}}`

- 무시되거나 최대 파일 크기를 초과하는 경로도 추적:

`jj file track --include-ignored {{경로/대상/파일_또는_디렉터리}}`
