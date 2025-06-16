# Face Liveness Check MCP Server

## Overview

The Face Liveness Check MCP server is a sophisticated tool designed to ensure that selfies submitted by users are genuine and captured live. It helps prevent fraud by verifying that the image is not a photo of a photo, a passport-sized image, or an image of another individual displayed on a screen. This service is crucial for maintaining the integrity of your records by confirming that the selfie is live and corresponds to the expected individual when paired with complementary facial recognition tools.

## What Does It Do?

The Face Liveness Check MCP server performs a series of checks on the submitted selfies to verify:

- **Liveness Detection**: Ensures that the face in the image is live and not a static picture.
- **Face Detection**: Identifies whether multiple faces are present in the image and calculates the percentage of the image each face covers.
- **Image Quality**: Assesses whether the image is optimally captured, including checks for cropping, lighting conditions, and distance from the camera.
- **Face Coordinates**: Provides the coordinates of where the face was captured within the image.

## How It Works

By supplying a selfie to the server, it analyzes several critical data points:

1. **Live Face Verification**: Determines if the face in the image is live.
2. **Face Crop Assessment**: Checks if the face is properly cropped within the image.
3. **Lighting Evaluation**: Evaluates whether the image is adequately lit.
4. **Proximity Analysis**: Assesses if the image is taken from an appropriate distance for optimal clarity.
5. **Face Coordinates**: Captures the precise location of the face within the image.

## Tools Provided

The Face Liveness Check MCP server offers the following tools for comprehensive face analysis:

- **Face Liveness Check**: Compares two face images and provides a match score. This tool requires a request ID to fetch results.
  
- **GET Call Tool**: Used to retrieve the results of the analysis using the request ID received in responses.

## Troubleshooting

If you encounter any issues while using the MCP server or have questions regarding its functionality, please reach out for assistance. Our support team is available to help resolve any concerns you might have.

For further inquiries or support, please contact your designated support representative.

---
This README provides an overview of the Face Liveness Check MCP server's capabilities and usage. For any additional information, please refer to the internal documentation or contact support.