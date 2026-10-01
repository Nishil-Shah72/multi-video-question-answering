# Multi-Video Question Answering System

A video-based question-answering system that allows users to ask questions and find relevant answers from information contained across multiple videos.

## Overview

Finding specific information from multiple videos can be time-consuming, especially when the required information is spread across different videos.

This project provides a system where users can ask a question in natural language, and the system searches through the processed content of multiple videos to identify the most relevant information and generate an answer.

Instead of manually watching every video, the user can simply ask a question and let the system find the relevant information.

## How It Works

The project follows a processing pipeline:

```text
Multiple Videos
       ↓
Extract Audio
       ↓
Convert Audio to Text
       ↓
Pre-process the Text
       ↓
Create Text Chunks
       ↓
Create Embeddings
       ↓
Store Processed Information
       ↓
User Question
       ↓
Search Relevant Information
       ↓
Generate Answer
