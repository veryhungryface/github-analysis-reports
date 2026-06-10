반드시 내장 image_gen 이미지 생성 도구를 사용해 새 PNG 인포그래픽을 생성하세요. HTML/SVG/PIL/Canvas/스크린샷/로컬 렌더링으로 대체하지 마세요. 결과 파일은 ./assets/doclang-project-doclang-infographic.png 로 복사/저장하세요.

Use case: infographic-diagram
Asset type: Korean repository analysis infographic for a GitHub Pages HTML report
Aspect: 16:9 landscape

Create a clean Korean infographic explaining the GitHub repository doclang-project/doclang.
Exact visible Korean text should be short and readable:
Title: DocLang: AI 문서 형식 표준
Subtitle: 구조·의미·레이아웃·좌표를 LLM 친화적 마크업으로 보존
Flow: 실제 문서 → DocLang 변환 → 검증 → LLM/VLM 활용
Cards:
1. 무엇인가: 비정형 문서를 AI-native XML로 표현
2. 핵심 가치: 구조·의미·좌표·레이아웃 보존
3. 검증: XSD + Schematron, CLI/Python API
4. 추천 대상: 문서 AI, OCR/추출, RAG 데이터셋 팀
5. 도입 전 확인: 자체 샘플 변환·검증 테스트

Visual style: clean technical schematic, bento grid, bright background, navy/teal/purple accents, abstract document icons, arrows, validator checkmark, AI node diagram. Large Korean text, high readability.
Strict exclusions: no recognizable logos, no GitHub logo, no IBM/NVIDIA/ABBYY/RedHat/LF AI logos, no product/company/engine logos, no endorsement badges, no watermark.

After generation, copy the selected generated raster from ~/.codex/generated_images/... to ./assets/doclang-project-doclang-infographic.png, then verify with file/identify. If image_gen is unavailable or fails, report failure; do not create a substitute image by code.
