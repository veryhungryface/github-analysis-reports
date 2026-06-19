Use the native image generation tool to create a Korean infographic image for a GitHub repository analysis report and save it to ./assets/vercel-eve-infographic.png.

Hard rules:
- Use ONLY native image generation / GPT image family real generation path.
- Do NOT use fallback or local synthesis: no Python/PIL, no SVG, no HTML screenshot, no ffmpeg, no ImageMagick, no copying existing files, no curl/download, no openai CLI.
- If native image generation is unavailable, fail without creating a substitute file.
- No recognizable company/product/engine logos; use generic icons only.
- Korean text should be simple and readable. Avoid tiny text.

Image spec:
- Landscape 16:9, clean premium tech infographic, bento-grid + technical schematic style.
- Title: "eve 한눈에 보기"
- Subtitle: "파일시스템으로 설계하는 지속형 AI 에이전트 프레임워크"
- Visual flow: "agent/ 폴더" → "컴파일·런타임" → "도구·채널·스케줄" → "운영 가능한 AI 에이전트"
- Benefit cards (short Korean labels):
  1. 구조가 보이는 에이전트
  2. 도구·스킬·서브에이전트 연결
  3. HTTP·Slack·Discord 채널
  4. 평가와 테스트 중심 운영
  5. Vercel 배포 친화적
- Small footer: "TypeScript · Apache-2.0 · Beta"
