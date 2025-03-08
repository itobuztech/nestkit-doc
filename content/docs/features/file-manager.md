---
title: File manger
weight: 2
---
# File Manager

The File Manager module provides a complete solution for handling files in your application with the following features:

## Core Features

### CRUD Operations
- **Create**: Upload new files with validation
- **Read**: Retrieve files with filtering options
- **Update**: Replace or modify existing files
- **Delete**: Remove files and related metadata

### Image Processing
- **Resize**: Automatically resize images to predefined dimensions
- **Crop**: Crop images with customizable options
- **Format Conversion**: Convert between different image formats

## Storage Options

### Local Storage
Files can be stored locally in the server filesystem with configurable paths.

### AWS Integration (Optional)
The file manager can be configured to use AWS S3 for file storage:

- S3 bucket storage
- Automatic upload/download
- Configurable access control

## Configuration

Enable AWS integration in your `.env` file:

```
AWS_S3_ENABLED=true
AWS_S3_BUCKET=your-bucket-name
AWS_ACCESS_KEY_ID=your-access-key
AWS_SECRET_ACCESS_KEY=your-secret-key
AWS_REGION=your-aws-region
```
