# Research History Index

> 모든 그래픽스 연구 문서의 중앙 인덱스

---

## 📁 Wicked Engine Deep Dive

**Repository**: https://github.com/insung52/Wicked-engine-Deep-Dive

### Wicked Engine 변경사항 추적
- **[Wicked Engine 2025년 3월 변경사항](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/wicked-follow/wickedfollow_3.md)** - 57개 커밋 분석 (Vehicle Physics, Capsule Shadow, SH GI, Camera Render Texture, Job System, Height Field 등)
- **[Wicked followup dx12 1](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/wicked-follow/wickedfollow_dx_1.md)** - Wicked Engine 2025년 3월 ~ 8월 DX12 변경사항 정리 및 VizMotive Engine 적용
- **[Wicked followup dx12 2](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/wicked-follow/wickedfollow_dx_2.md)** - Wicked Engine 2025년 9월 ~ 2026년 1월 DX12 변경사항 정리 및 VizMotive Engine 적용
- **[DX12 변경사항 주제별 분류 README](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/wicked-follow/topics/README.md)** - 44개 커밋을 7개 주제로 분류. topic_(분석) / apply_(VizMotive 적용) / appendix_(개념) 문서 구조 안내

### Vizmotive MCP
- **[Vz MCP plan](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/vz_mcp/plan.md)** - Vizmotive Engine mcp 화 개발 계획 정리 문서
- **[Vz MCP developement report 260113](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/vz_mcp/VizMotive_MCP_Implementation_Report.md)** - Vizmotive Engine script, mcp 연결 리포트 (260113)
- **[instanceResLookupUploadBuffer size error](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/vz_mcp/Fix_instanceResLookupUploadBuffer_size.md)** - buffer 크기를 잘못 할당하던 오류 해결
- **[Vz MCP development report 260118](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/vz_mcp/Vz_mcp_development_0118.md)** - Vizmotive Engine script, mcp 연결 업데이트 리포트 (260118)

### Particle System (VizMotive Engine)
- **[Particle Implementation Documentation](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_documentation.md)** - VizMotive Engine GPU 기반 파티클 시스템 전체 구현 과정 (Emit, Simulate, Sort, Double Buffering, Flickering 버그 해결)
- **[Particle Implementation Plan](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_plan.md)** - 초기 파티클 시스템 구현 계획서
- **[Particle Implementation Plan v2 Material](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_plan_v2_material.md)** - Material 통합 구현 계획서 (Base Color, Emissive)
- **[Particle Memo](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/memo.md)** - 파티클 시스템 개발 중 메모 및 디버깅 노트

### DDGI (Dynamic Diffuse Global Illumination)
- **[DDGI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI.md)** - DDGI 전체 시스템 분석 (Probe 배치, Ray Tracing, SH 계산, Variance Shadow Map)
- **[DDGI Raytracing Flow](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI_Raytracing_Flow.md)** - DDGI Raytracing 상세 과정 (BLAS/TLAS 생성, Surface Data 로드, Lighting 계산)
- **[VizMotive DDGI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/vizmotive%20DDGI.md)** - VizMotive Engine DDGI 이식 및 Winding Order 문제 해결 (RHS ↔ LHS)
- **[DDGI Material Bug](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI_material_error.md)** - VizMotive Engine DDGI Material Sampling Bug 해결
- **[DDGI probe shadow Fix](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI_probe_shadow_fixes.md)** - VizMotive Engine DDGI 관련 probe 의 shadow 처리 오류 해결

### Shadow Mapping
- **[Cascade Shadow Map](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/shadow/cascade_shadow_map.md)** - CSM 구현 원리 및 Dithering 기법 (Bayer Matrix, Blue Noise, Temporal Blending)
- **[Capsule Shadow](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/shadow/capsule_shadow.md)** - 캡슐 형태 Soft Shadow 구현 (캐릭터 접지 그림자, Cone 기반 Occlusion)
- **[ShadowMap_Display_Error](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/shadow/shadow_map_error_2.md)** - GUI "Show Shadow Map" 버튼 클릭 시 D3D12 경고 발생 문제 해결
- **[Point Light Shadow](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/shadow/PointLightShadow.md)** - VizMotive Engine Point Light 에 Shadow 구현

### Voxel GI
- **[Voxel GI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/voxelGI/voxelGI.md)** - Voxel 기반 Global Illumination 전체 파이프라인 (Voxelization, Light Injection, Propagation, ClipMap)

### 기본 개념 정리 (study/)

그래픽스/C++ 기초 개념 문서. topic/apply 문서 읽기 전 배경 지식용.

**그래픽스 (`study/graphics/`)**
- part0: 컴퓨터 기초 / part1: 그래픽스 기초 / part2: 그래픽스 파이프라인
- part3: GPU 통신 / part4: 리소스 관리 / part5: 텍스처 라이프사이클 / part6: PSO 엔진 구현

**C++ (`study/lan/c++/`)**
- 포인터·참조 / 비트 연산과 플래그 / 람다와 캡처 / const·constexpr
- 스마트 포인터·RAII / 템플릿·매크로 / 구조체·초기화 / placement new

---

## 📁 Blender Terrain MCP

**Repository**: https://github.com/insung52/blender-terrain-mcp

### AI-Powered 3D Terrain Generator
- **[README](https://github.com/insung52/blender-terrain-mcp/blob/main/README.md)** - AI 기반 3D 지형 생성 웹 애플리케이션 (Biome 레이아웃, 도로 시스템, 오브젝트 배치, GLB Export)

---

## 📊 Timeline

### 2026-03
- **Point Light Shadow 구현** - Frustum culling (RHS/LHS mismatch), Cubemap camera quaternion, ENTITY_FLAG_LIGHT_CASTING_SHADOW 미설정 등 3개 버그 수정
- **DDGI probe shadow 수정** - FLAG_FORCE_OPAQUE TLAS 적용, light_axis 기본 OFF + 그림자 캐스팅 비활성화, backface early return 제거 (WickedEngine 동일 동작으로 복원)
- **DX12 변경사항 주제별 분류 README 작성** - topic_(분석) / apply_(VizMotive 적용) / appendix_(개념) 구조 정리

### 2026-01
- **Wicked Engine 2025년 3월 변경사항 분석** - 57개 커밋 분석 및 VizMotive 비교 (SH GI, Capsule Shadow, Job System 등)
- **Capsule Shadow 문서 작성** - 캡슐 형태 Soft Shadow 구현 원리 분석
- **Particle System Flickering 해결** - Double buffering swap 타이밍 수정 (GPU 커맨드 전으로 이동)
- **Particle Emissive Color 구현** - RGB emissive color + strength 분리

### 2025-12
- **DDGI Winding Order 문제 해결** - RHS CCW geometry의 DXR 호환성 수정

### 2025-11
- **Particle System 구현 완료** - GPU-driven particle system with sorting

### 2025-10
- **DDGI 연구 시작** - Probe 배치, Ray tracing, SH 계산

---

## 🔍 Quick Reference

### GPU Particle System
- **Double Buffering**: [Particle Documentation](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_documentation.md#double-buffering-strategy)
- **Bitonic Sort**: [Particle Documentation](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_documentation.md#phase-4-sorting-system)
- **Flickering Bug**: [Particle Documentation](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_documentation.md#phase-7-critical-bug---flickering)

### DDGI
- **Ray Tracing**: [DDGI Raytracing Flow](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI_Raytracing_Flow.md)
- **Winding Order**: [VizMotive DDGI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/vizmotive%20DDGI.md#문제-원인)
- **Chebyshev Inequality**: [DDGI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI.md#raydatadirection_distance-용도)

### Shadow & GI
- **Cascade Shadow Map**: [CSM](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/cascade_shadow_map/cascade_shadow_map.md)
- **Voxel GI**: [Voxel GI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/voxelGI/voxelGI.md)

---

## 📝 Notes

- 모든 문서는 Markdown 형식으로 작성됨
- 코드 예시는 주로 C++/HLSL
- 이미지 및 다이어그램 포함
- 실제 구현 코드 경로: `C:\graphics\vizmotive\origin\VizMotive-Engine`

---

**Last Updated**: 2026-03-12
