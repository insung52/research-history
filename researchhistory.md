# Research History Index

> 모든 그래픽스 연구 문서의 중앙 인덱스

---

## 📁 Wicked Engine Deep Dive

**Repository**: https://github.com/insung52/Wicked-engine-Deep-Dive

### Wicked Engine 변경사항 추적
- **[Wicked Engine 2025년 3월 변경사항](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/wicked-follow/wickedfollow_3.md)** - 57개 커밋 분석 (Vehicle Physics, Capsule Shadow, SH GI, Camera Render Texture, Job System, Height Field 등)
- **[Wicked followup dx12 1](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/wicked-follow/wickedfollow_dx_1.md)** - Wicked Engine 2025년 3월 ~ 8월 DX12 변경사항 정리 및 VizMotive Engine 적용
- **[Wicked followup dx12 2](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/wicked-follow/wickedfollow_dx_2.md)** - Wicked Engine 2025년 9월 ~ 2026년 1월 DX12 변경사항 정리 및 VizMotive Engine 적용

### Vizmotive MCP
- **[Vz MCP plan](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/vz_mcp/plan.md)** - Vizmotive 엔진 mcp 화 개발 계획 정리 문서
- **[Vz MCP developement report 260113](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/vz_mcp/VizMotive_MCP_Implementation_Report.md)** - Vizmotive 엔진 script, mcp 연결 리포트 (260113)
- **[instanceResLookupUploadBuffer size error](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/vz_mcp/Fix_instanceResLookupUploadBuffer_size.md)** - buffer 크기를 잘못 할당하던 오류 해결
- **[Vz MCP development report 260118](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/vz_mcp/Vz_mcp_development_0118.md)** - Vizmotive 엔진 script, mcp 연결 업데이트 리포트 (260118)

### Particle System
- **[Particle Implementation Documentation](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_documentation.md)** - GPU 기반 파티클 시스템 전체 구현 과정 (Emit, Simulate, Sort, Double Buffering, Flickering 버그 해결)
- **[Particle Implementation Plan](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_plan.md)** - 초기 파티클 시스템 구현 계획서
- **[Particle Implementation Plan v2 Material](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/particle_implementation_plan_v2_material.md)** - Material 통합 구현 계획서 (Base Color, Emissive)
- **[Particle Memo](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/particle/memo.md)** - 파티클 시스템 개발 중 메모 및 디버깅 노트

### DDGI (Dynamic Diffuse Global Illumination)
- **[DDGI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI.md)** - DDGI 전체 시스템 분석 (Probe 배치, Ray Tracing, SH 계산, Variance Shadow Map)
- **[DDGI Raytracing Flow](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI_Raytracing_Flow.md)** - DDGI Raytracing 상세 과정 (BLAS/TLAS 생성, Surface Data 로드, Lighting 계산)
- **[VizMotive DDGI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/vizmotive%20DDGI.md)** - VizMotive Engine DDGI 이식 및 Winding Order 문제 해결 (RHS ↔ LHS)
- **[DDGI Material Bug](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/DDGI/DDGI_material_error.md)** - DDGI Material Sampling Bug 해결

### Shadow Mapping
- **[Cascade Shadow Map](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/shadow/cascade_shadow_map.md)** - CSM 구현 원리 및 Dithering 기법 (Bayer Matrix, Blue Noise, Temporal Blending)
- **[Capsule Shadow](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/shadow/capsule_shadow.md)** - 캡슐 형태 Soft Shadow 구현 (캐릭터 접지 그림자, Cone 기반 Occlusion)
- **[ShadowMap_Display_Error](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/shadow/shadow_map_error_2.md)** - GUI "Show Shadow Map" 버튼 클릭 시 D3D12 경고 발생 문제 해결

### Voxel GI
- **[Voxel GI](https://github.com/insung52/Wicked-engine-Deep-Dive/blob/main/voxelGI/voxelGI.md)** - Voxel 기반 Global Illumination 전체 파이프라인 (Voxelization, Light Injection, Propagation, ClipMap)

---

## 📁 Blender Terrain MCP

**Repository**: https://github.com/insung52/blender-terrain-mcp

### AI-Powered 3D Terrain Generator
- **[README](https://github.com/insung52/blender-terrain-mcp/blob/main/README.md)** - AI 기반 3D 지형 생성 웹 애플리케이션 (Biome 레이아웃, 도로 시스템, 오브젝트 배치, GLB Export)

---

## 📊 Timeline

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

**Last Updated**: 2026-01-25
