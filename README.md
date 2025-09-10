# ARM64-Compatible ImageProxy Docker Image

This repository hosts an ARM64-compatible Docker image of [willnorris/imageproxy](https://github.com/willnorris/imageproxy), a caching and resizing image proxy written in Go.

## 📦 Image Location
```
docker pull ghcr.io/maddoglee/imageproxy:arm64
```

## 🖥️ Architecture Compatibility
This image is built for:
- `linux/arm64` (e.g., Raspberry Pi 4, Rock Pi 4, Jetson Nano)

## 🚀 Usage
You can run the image using Docker Compose:

```yaml
services:
  imageproxy:
    image: ghcr.io/maddoglee/imageproxy:arm64
    ports:
      - "8080:8080"
```

Or directly with Docker:
```bash
docker run -d -p 8080:8080 ghcr.io/maddoglee/imageproxy:arm64
```

## 📄 License
This image is based on the original [willnorris/imageproxy](https://github.com/willnorris/imageproxy) project, which is licensed under the MIT License.

## ⚠️ Disclaimer
This image is provided as-is, without warranty or guaranteed support. It is maintained independently by [maddoglee](https://github.com/maddoglee) and is not affiliated with the original author.

Feel free to open issues or contribute if you'd like to improve ARM64 support!
