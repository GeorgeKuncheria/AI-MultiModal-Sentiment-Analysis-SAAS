![alt text](thumbnail.png)

## Overview



Features:

- 🎥 Video sentiment analysis
- 📺 Video frame extraction
- 🎙️ Audio feature extraction
- 📝 Text embedding with BERT
- 🔗 Multimodal fusion
- 📊 Emotion and sentiment classification
- 🚀 Model training and evaluation
- 📈 TensorBoard logging
- 🚀 AWS S3 for video storage
- 🤖 AWS SageMaker endpoint integration
- 🔐 User authentication with Auth.js
- 🔑 API key management
- 📊 Usage quota tracking
- 📈 Real-time analysis results
- 🎨 Modern UI with Tailwind CSS

## Setup

Follow these steps to install and set up the SaaS project:

### Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-video-sentiment-saas.git
cd ai-video-sentiment-saas
```

2. Install dependencies

```
npm install
```

3. Configure environment variables in .env:

```
DATABASE_URL="your-database-url"
AUTH_SECRET="your-auth-secret"
AWS_REGION="your-aws-region"
AWS_ACCESS_KEY_ID="your-access-key"
AWS_SECRET_ACCESS_KEY="your-secret-key"
```

4. Initialize the database:

```
npm run db:generate
npm run db:push
```

## Running the app

### Development

```
npm run dev
```

### Production

```
npm run build
npm start
```
