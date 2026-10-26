### Project_404: Tomorrow Not Found
🏹 CO-OP 루터 슈터 · 서바이벌 보스 레이드<br>

| 구분 | 내용 |
| --- | --- |
| 게임명 | Project_404: Tomorrow Not Found |
| 게임 장르 | CO-OP 루터 슈터 · 서바이벌 보스 레이드 |
| 플랫폼 | PC (Windows) |
| 개발 인원 | 5인 |
| 사용 엔진 | Unreal Engine 5.6.1 (C++) |
| 네트워크 | Listen Server 기반 멀티플레이 |
| 핵심 기술 | Gameplay Ability System (GAS) |
| 프로젝트 기간 | 2026.05.01 ~ 2026.05.27 (27일) |
| 플레이 빌드 | [Google Drive](https://drive.google.com/drive/folders/12ftKhGUnKpf9qITEDEhA8A2viajg5-pE?usp=sharing) |
| 개발 내용 | [Notion](https://www.notion.so/dalssagi/Project4-33ebf57640cf80408a2afa3b783b093d?source=copy_link) |

## 게임 소개

*💡원티드 포텐업 게임 개발 트랙 4기에서 제작한 팀 프로젝트입니다.* <br>
<table>
  <tr>
    <td>
      플레이어들이 협력하여 전투 지역을 탐색하고, 적을 처치하며 획득한 무기 부품으로 장비를 제작해 최종 보스에 도전하는 <strong>CO-OP 루터 슈터 및 서바이벌 보스 레이드 게임</strong>이다.
      <br><br>
      일반 전투 구역에서 <strong>무기 부품을 파밍하고, 레시피 기반 크래프팅으로 무기를 제작</strong>하며 보스전에 대비한다.
      <br><br>
      <strong>협동 전투를 통한 생존, 파밍과 제작을 통한 장비 구성, 강력한 보스를 공략하는 성취감</strong>이 핵심 재미이다.
    </td>
  </tr>
</table>

> **핵심 게임플레이 구조**
>
> 로비 → 일반 필드 전투 및 무기 부품 파밍 → 무기 크래프팅 → 협동 보스 레이드 → 스테이지 클리어
  
## 게임 영상

[게임 플레이 영상(Google Drive)](https://drive.google.com/drive/folders/1rLVa4iH-lfI2jdPqP1vcwc_oQOil1DVx?usp=sharing)

## 개발 내용

[상세 개발 내용(Notion)](https://www.notion.so/dalssagi/Project4-33ebf57640cf80408a2afa3b783b093d?source=copy_link)
1. **GAS(Gameplay Ability System) 기반 전투 및 무기 시스템**
   - GAS 프레임워크를 활용한 전투 및 무기 기능 구현
   - 어빌리티 기반의 전투 동작과 시스템 구성

2. **Listen Server 기반 CO-OP 멀티플레이**
   - Listen Server 구조를 활용한 멀티플레이 환경 구현
   - RPC 및 Replication을 통한 서버·클라이언트 간 게임 상태 동기화

3. **단계별 게임플레이 루프 및 진행 시스템**
   - 로비 → 일반 필드 파밍 → 무기 제작 → 보스 레이드로 이어지는 게임 진행 구조
   - 전투 단계별 게임 상태 관리 및 전환

4. **몬스터 AI 및 보스 AI**
   - Behavior Tree를 활용한 몬스터 및 보스 행동 로직
   - Primary Data Asset(PDA)을 활용한 데이터 관리

5. **레시피 기반 무기 크래프팅 시스템**
   - 전투 보상으로 획득한 무기 부품을 활용한 제작 시스템
   - 레시피에 따른 무기 조합 및 파밍·제작·전투의 연계

6. **Level Sequence 기반 시네마틱 연출**
   - Unreal Engine Level Sequence를 활용한 시네마틱 연출
   - 게임 진행 및 주요 전투 상황에 따른 연출 구성

## 리소스 출처

- 3D 캐릭터 애니메이션: [Mixamo](https://www.mixamo.com/)
- VFX, 환경, 구조물, 캐릭터, 사운드: [Fab](https://www.fab.com/)

## 보완할 점
| 구분 | 피드백 및 문제점 | 개선 방향 |
|:---:|---|---|
| **레벨 디자인** | 레벨의 밀도와 전투 페이싱이 부족하여 플레이 경험이 다소 단조로움 | 적 배치, 전투 구역 간 이동 거리 및 인카운터 구성을 조정하여 **전투의 완급 조절과 레벨 밀도 개선** |
| **보스전 완성도** | 보스전 도우미 로봇 등 일부 기능이 미완성되어 의도한 전투 경험을 충분히 제공하지 못함 | 미완성 기능을 보완하고, 보스전 기믹과 협동 요소를 추가 검증하여 **보스 레이드의 완성도 향상** |

## 프로젝트 성과
- 플레이테스트를 통해 **무기 부품 파밍과 레시피 기반 크래프팅을 통한 장비 제작** 등 핵심 게임플레이 요소의 재미에 대한 긍정적인 반응을 확인하였다.
- **로비 → 일반 필드 전투 및 무기 부품 파밍 → 무기 크래프팅 → 협동 보스 레이드 → 스테이지 클리어**로 이어지는 핵심 게임플레이 루프를 구현하고, **1개 스테이지를 완성하였다.**
