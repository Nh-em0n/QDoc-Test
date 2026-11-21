It depends on whether you want to embed an editor (users draw in your app) or embed rendered diagrams (show diagrams on a page).

**Embed an editable canvas in your app**
- **tldraw**: React component (`<tldraw>`) with a polished UI, a good SDK, and custom shapes. Check its license, since production use can require a license key.
- **Excalidraw**: Also an npm React component (`@excalidraw/excalidraw`), MIT licensed, with the hand-drawn look.
- **draw.io**: Embed via iframe with its embed mode and postMessage API. It's free, and it's the most full-featured for formal diagrams.
- **React Flow (xyflow)**: Best for node-and-edge editors such as workflow builders, pipelines, and mind maps. It's more of a library for building diagram UIs than a drawing tool.
- **JointJS / GoJS / yFiles**: Commercial-grade libraries for complex diagramming apps, with licensing costs.

**Embed rendered diagrams in a page or docs**
- **Mermaid**: Include the JS library and write diagrams as text in a `<pre class="mermaid">` block. It also renders natively in GitHub, GitLab, and Notion.
- **D2**: Compiles to SVG, which you can drop into any page.
- **Excalidraw / draw.io exports**: Export to SVG or PNG and embed it like any image. Both can also embed the scene data in the file so it stays editable.
- **Kroki**: A service that renders many text diagram formats (Mermaid, PlantUML, D2, and more) to SVG through a URL.

**Quick picks**
- Whiteboard inside your React app: **tldraw** or **Excalidraw**
- Workflow or node editor: **React Flow**
- Docs or blog with diagrams as code: **Mermaid**
- Formal diagrams embedded via iframe: **draw.io**

If you tell me your stack (React, plain HTML, Next.js, etc.) and whether users need to edit the diagrams, I can show a minimal embed example.</pre></tldraw>