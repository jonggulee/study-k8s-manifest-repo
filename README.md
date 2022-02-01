base : kubernetes manifest 원본이 위치한 디렉토리 입니다. 이 안에 위치한 manifest 들은 overlays 아래에 위치한 kustomize.yaml 파일에 담긴 사용자 지정 설정 내용에 따라 변경 변경 되어 집니다.

overlays : 사용자 입맛에 맞는 설정 값이 위치한 디렉토리 입니다. 이 설정은 kustomize.yaml 에 담습니다. 이 하위에 있는 dev 디렉토리는 실습을 위해 만든 것으로, 개발 환경에 적용할 설정 파일을 모아 두기 위함 입니다.
