git 협업 방법(github desktop사용)

각자코딩을 해서 합치는 방법 - git사용

New repository 새로운 저장소 생성
코딩을 하기위해 저장소 다운
로컬에 저장소 경로에 임의의 코드와 이미지등을 추가하면 바로 GitHub Desktop에 바로 반영
여기서 주의해야 할 점은 변경내용에 대한 커밋은 아직 로컬 저장소에만 있다는 것이다. 즉, 로컬 저장소 내용을 GitHub저장소에 반영해야 한다.
##오른쪽 연필 모양의 편집 아이콘을 클릭하여 직접 내용을 변경합니다. 간단한 설명을 추가하도록 하겠습니다. 

Collaborators
저장소의 소유자는 필요한 경우 해당 저장소의 코드와 관리를 할 수 있는 다른 사용자를 Collaborator로서 등록할 수 있습니다.
Settings 탭의 Collaborators항목을 선택하면 해당 저장소에서 같이 협업할 수 있는 사용자를 추가하고 관리할 수 있습니다.

FORK
해당 저장소에 등록된 협업 사용자가 아니라 하더라도 해당 저장소를 fork하면 자신의 저장소로 복제할 수 있습니다.

Pull Request
정하고 다시 fork한 원본 저장소에 반영해달라고 요청하는 기능


우선 현재 저장소를 fork하기 위해 화면 오른쪽에 Fork라는 버튼을 클릭
Forked된 저장소는 어느 저장소로부터 fork되었는지 표시되며, 해당 저장소의 commit 기록도 복제됩니다.
fork한 저장소에서 수정후 commit하면 REAMME.md의 내용이 변경

Commit 로그 오른쪽에 표시된 Pull Request 버튼을 클릭하면, 해당 commit까지에 대한 변경 내용을 원본 저장소로 반영하려는 요청 화면이 표시됩니다.
당 요청에 대한 변경 정보와 commit 정보가 표시되며 원본 저장소에 해당 PR이 반영되는 경우 문제가 발생 할 수 있는지에 대한 정보를 표시합니다. 문제가 없는 경우라면 Create pull request 버튼을 클릭하여 요청을 진행합니다.
생성하는 요청에 대한 comment를 입력후 Create pull request 버튼을 클릭하여 요청을 진행합니다.
해당 요청을 클릭하면 누가 해당 요청을 생성했고 어떤 내용이 변경되었는지에 대한 내역을 볼 수 있습니다. 
요청이 정상적으로 통합될 수 있는 경우 Merge pull request 버튼을 클릭하고 Confirm merge를 눌러 해당 요청을 반영합니다.

출처-https://developer.ibm.com/kr/developer-%EA%B8%B0%EC%88%A0-%ED%8F%AC%EB%9F%BC/2018/02/05/github-collaboration/