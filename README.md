<div align="center">
  <img src="https://res.cloudinary.com/ddjsyskef/image/upload/v1748228419/public/yjunxp9mrx9ae00irdft.png" alt="UI Attachment Inspector" />
</div>


# UI Attachment Inspector

An application that allows you to inspect and analyze UI elements from images. This tool helps developers and designers understand the structure and components of web interfaces, and the Prompt result able to generate app with Code Builder likes [Bolt](https://bolt.new), [V0](https://v0.dev), [Loveable](https://loveable.dev), and [Firebase Studio](https://studio.firebase.google.com).

## Features

- Upload and analyze UI screenshots
- AI-powered UI element detection and analysis, using [Genkit](https://genkit.dev/)
- Support for PNG, JPG, GIF, and WEBP formats
- Drag and drop interface
- Real-time analysis results
- Copy analysis to clipboard
- Dark/Light theme support

## Prerequisites

- Node.js 18.x or later
- npm or yarn package manager

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/ekaone/attachment-inspector
cd attachment-inspector
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env.local` file in the root directory and add your environment variables:
```env
# GEMINI_API_KEY=
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:9002`

## Usage

1. Open the application in your browser
2. Drag and drop an image or click to select a file
3. Wait for the AI analysis to complete
4. View the results and copy them to your clipboard if needed

## Supported File Types

- PNG
- JPG/JPEG
- GIF
- WEBP

Maximum file size: 10MB

## Development

The main application code is located in `src/app/page.tsx`. Key components and features are organized in the following structure:

- `src/components/` - UI components
- `src/hooks/` - Custom React hooks
- `src/lib/` - Utility functions
- `src/ai/` - AI analysis related code

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the repository or contact the maintainers.


