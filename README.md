# 커비 서바이버즈 다운로드

Mac·Windows용 개발 테스트판의 실행본과 실행 안내를 제공합니다.

## 다운로드

**[v0.1.0-alpha.1 프리릴리즈 다운로드](https://github.com/ninpeng/kirby-survivors-downloads/releases/tag/v0.1.0-alpha.1)**

| 대상 | 파일 | 확인 상태 |
| --- | --- | --- |
| Mac Apple Silicon ARM64 | [Mac ZIP · 약46.6MB](https://github.com/ninpeng/kirby-survivors-downloads/releases/download/v0.1.0-alpha.1/Kirby-Survivors-macOS-AppleSilicon.zip) | 개발에 사용한 Mac에서 **실행 확인 완료** |
| Windows x64 | [Windows ZIP · 약55.3MB](https://github.com/ninpeng/kirby-survivors-downloads/releases/download/v0.1.0-alpha.1/Kirby-Survivors-Windows-x64.zip) | **빌드·패키지 확인까지 완료**, 실제 Windows 실행 미확인 |

플레이하려면 위의 운영체제별 실행본 ZIP을 받으세요. GitHub가 자동 제공하는 `Source code` 압축파일은 이 다운로드 안내 저장소의 문서입니다.

## Mac 실행

1. Mac ZIP을 다운로드하고 압축을 완전히 풉니다.
2. `Kirby Survivors.app`을 더블 클릭합니다.
3. **함께 떠나요! → 모험 시작**을 선택합니다.
4. 앱 종료 메뉴 또는 `⌘Q`로 종료합니다.

Apple Silicon ARM64용이며 Intel Mac용 빌드는 포함하지 않습니다. Unity Editor나 별도 웹 서버를 설치할 필요는 없습니다. 개발 테스트용 ad-hoc 서명 빌드로, Developer ID 서명·Apple 공증은 진행하지 않았습니다. 다운로드한 앱의 다른 Mac 실행·보안 확인은 별도로 확인해야 합니다.

## Windows 실행

1. Windows ZIP 전체를 한 폴더에 압축 해제합니다.
2. `Kirby-Survivors-Windows-x64` 폴더 안의 `Kirby Survivors.exe`를 실행합니다.
3. 동봉된 `Kirby Survivors_Data`, `UnityPlayer.dll`, `MonoBleedingEdge`, `D3D12` 등 파일·폴더를 함께 유지합니다.
4. **함께 떠나요! → 모험 시작**을 선택합니다.

Windows용 Unity Editor를 설치할 필요는 없습니다. **Windows는 크로스 빌드 성공과 패키지 구성·무결성 확인까지만 완료했으며, 실제 Windows 기기에서 실행·조작·소리는 아직 확인하지 않았습니다.**

## 조작

| 입력 | 동작 |
| --- | --- |
| `WASD` 또는 방향키 | 이동 |
| `F` | 가까운 새 능력 별의 복사·교체 선택 |
| `G` | 조합 가능한 능력의 합성 선택 |
| `1` / `2` / `3` 또는 카드 클릭 | 레벨업 강화 선택 |
| `Esc` | 전투 일시정지·메뉴 |
| 마우스 클릭 | 로비·설정·능력·강화 선택 |

기본 흡입·별 뱉기와 장착 능력의 공격은 자동입니다. 떨어뜨린 자신의 흰 별은 가까이에서 자동으로 회수합니다. 네이티브 앱의 기록·설정은 웹 버전과 별도로 저장됩니다.

## 확인 범위

- Mac은 개발에 사용한 Apple Silicon 기기에서 타이틀→로비→전투, 이동·방향 전환·정지, 일시정지와 정상 종료를 확인했습니다.
- Windows 실제 실행, 다른 기기의 성능과 후반 최대 부하는 아직 확인하지 않았습니다.
- 최종 밸런스 조정 전의 프리릴리즈입니다.
- 비공식 커비 팬 프로젝트입니다. 캐릭터·음원 관련 권리와 공개 배포 범위는 추가 확인이 남아 있습니다.
