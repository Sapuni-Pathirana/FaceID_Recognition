2026-06-26T00:40:38+05:30 - fix(registration): fix indentation corruption in tools and resolve ArcFace double-cropping error during video registration
2026-06-26T00:06:32+05:30 - Exclude .env and database files from rsync deletion
2026-06-25T23:50:20+05:30 - Fix SSH key handling in deploy.yml
2026-06-25T23:47:00+05:30 - automatically append trailing newline to deploy private key
2026-06-25T23:24:37+05:30 - support fallback secret name SSH_PRIVATE_KEY for VPS authentication
2026-06-25T23:08:33+05:30 - fix easingthemes/ssh-deploy configuration mapping by using env block
2026-06-25T23:03:26+05:30 - update github actions deployment workflow with 4 checks
2026-06-25T23:03:23+05:30 - add recognition and liveness workflow integration test suite
2026-06-25T23:03:21+05:30 - add enrollment workflow integration test suite
2026-06-25T21:38:06+05:30 - chore: clean up temporary face embedding test files
2026-06-25T21:37:56+05:30 - test: add unit test suite for database, detection, recognition, and APIs
2026-06-25T21:37:51+05:30 - feat(docker): add production multi-stage Dockerfile and docker-compose
2026-06-25T21:37:46+05:30 - feat(logging): add structured JSON logging formatting support
2026-06-25T21:37:42+05:30 - feat(web): add WebSocket live stream and batch recognition API endpoints
2026-06-25T21:37:37+05:30 - feat(recognition): integrate FAISS indexing and exponential decay drift prevention
2026-06-25T21:37:32+05:30 - feat(quality): implement face image quality gate for registration
2026-06-25T21:37:23+05:30 - feat(db): implement thread-local connection pooling and sequential schema migrations
2026-06-25T21:37:18+05:30 - feat(detection): implement OpenCV DNN face detector using ResNet-10 SSD
2026-06-25T21:25:49+05:30 - docs: Remove emojis from documentation headers
2026-06-25T21:24:47+05:30 - docs: Consolidate and clean up scattered intermediate markdown files
2026-06-25T21:09:18+05:30 - feat: Integrate trained liveness model into webcam loop and web APIs
2026-06-25T20:37:58+05:30 - docs: add empirical benchmark results and plot images to README
2026-06-25T18:54:21+05:30 - feat(notebooks): fully populate all evaluation and benchmark notebooks with execution cells
2026-06-25T18:52:05+05:30 - feat(notebooks): populate 04_liveness_detection.ipynb with dataset loader and training cells
2026-06-25T14:51:02+05:30 - docs: fully update README with modern modules, architectures, and remove emojis
2026-06-25T14:48:50+05:30 - feat: add sample face thumbnails, embedding files, and fix environment variable configuration syntax
2026-06-25T14:42:58+05:30 - fix(recognition): resolve face_image NameError during registration and adjust image inputs for different recognizers
2026-06-25T14:33:36+05:30 - fix(recognition): Fix ArcFace 'No Face Detected' errors by passing full images instead of tightly cropped faces
2026-06-25T14:24:00+05:30 - feat(detection): Upgrade default face detector to RetinaFace for enhanced accuracy
2026-06-25T14:21:25+05:30 - fix(ui): Return 400 Bad Request instead of 500 Server Error when face detection fails during registration
2026-06-25T14:04:09+05:30 - fix(ui): Resolve Jinja2 500 template error by providing valid fallback stats schema and safely accessing thresholds
2026-06-25T14:00:34+05:30 - feat(config): Integrate python-dotenv for flexible configuration management
2026-06-25T13:43:11+05:30 - fix: Update startup scripts and main entry point to handle runtime arguments
2026-06-25T13:14:07+05:30 - refactor: Reorganize project architecture, implement multi-face support, and fix core security vulnerabilities
2026-06-25T13:14:07+05:30 - docs: Consolidate markdown reports and update guides
2026-06-25T13:14:07+05:30 - feat(ml): Add liveness detection, face quality assessment, and experiment notebooks
2026-06-25T13:14:07+05:30 - feat(ml): Add ArcFace fine-tuning pipeline and biometric evaluation framework
2026-06-25T13:14:07+05:30 - feat(ui): Implement Neumorphic UI design system
2025-10-26T03:57:47+05:30 - Comprehensive system cleanup complete - Removed 36 files, 4051 directories, cleaned 1664 database records, freed space and optimized system
2025-10-26T03:51:04+05:30 - Fix comprehensive person deletion system - Now properly deletes all data from face identity manager, recognition database, video frames, uploads, and database records
2025-10-26T03:40:52+05:30 - Re-enable continuous learning (auto learning) system - Fixed variable name issue and enabled automatic model updates during recognition
2025-10-26T03:37:06+05:30 - Advanced Face Recognition System Complete - Face alignment, adaptive thresholding, enhanced lighting normalization, feature normalization, and performance analysis implemented
2025-10-24T04:52:53+05:30 - Clean up repository: Remove unwanted files and optimize structure
2025-10-24T04:43:29+05:30 - Initial commit: Ultimate Multi-Model Face Recognition System
