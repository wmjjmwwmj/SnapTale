# SnapTale
Record your life on the fly!


[![Watch the video](https://img.youtube.com/vi/T-D1KVIuvjA/maxresdefault.jpg)](//player.bilibili.com/player.html?isOutside=true&aid=113000438565432&bvid=BV13XWaecEYa&cid=500001657377903&p=1)



## Tech Stacks

- **Backend**: Powered by [FastAPI](https://fastapi.tiangolo.com/) and [MySQL](https://www.mysql.com/).
- **Frontend**: Built using [React](https://reactjs.org/).
- **DevOps**: [GitHub Actions](https://docs.github.com/en/actions), Alibaba Cloud [Apsara DevOps](https://www.alibabacloud.com/help/en/oos/getting-started/create-an-apsara-devops-pipeline-to-deploy-applications), and [Docker](https://www.docker.com/get-started/) for containerization.

## Features

1. **Moment Capture**: Record and summarize significant moments in your life.
2. **Content Management**: Organize and manage your photos and journal entries.
3. **Life Suggestions**: Use your journal to receive personalized life advice and mental health support.
4. **Daily Reflection**: Reflect on your day with insightful prompts and monitor mental health status.
5. **Meta-Information Tracking**: Automatically record timestamps and GPS locations for each entry.
6. **Activity Visualization**: Visualize your activity status through interactive heatmaps.
7. **Social Media Sharing**: Share your content with friends on social media platforms.
8. **Data Insights**: Analyze trends and patterns in your entries to gain deeper insights into your activities and emotions.
9. **Customizable Reminders**: Set reminders for journaling and capturing moments based on your preferences.
10. **Multi-Device Syncing**: Sync your data across multiple devices for seamless access and management.
11. **Privacy Controls**: Manage who can view and interact with your content through robust privacy settings.
12. **Export Options**: Export your data in various formats (e.g., PDF, CSV) for backup or sharing purposes.



## Roadmap

- [x] Infra setup: building backend.
- [x] Gallery and journal display.
- [x] Generate journal entries with photos.
- [x] User profile display with activity heatmap.
- [ ] Future updates will include integration with small portable devices. (_WIP_)

## Getting Started

### Running with Docker

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/SnapTale.git
   ```

2. **Build and start the Docker containers**:
   ```bash
   cd SnapTale
   docker-compose up --build
   ```
   This command will build and start both the frontend and backend services, as well as the MySQL database.

3. **Access the application**:
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend: [http://localhost:8000](http://localhost:8000)

### Manual Setup

If you prefer to run the project manually:

1. **Backend Setup**:
   - Navigate to the backend directory and install dependencies:
     ```bash
     cd backend
     pip install -r requirements.txt
     ```
   - Configure your MySQL database and set environment variables.

2. **Frontend Setup**:
   - Navigate to the frontend directory and install dependencies:
     ```bash
     cd frontend
     npm install -g pnpm
     pnpm install
     ```

3. **Running the Project**:
   - Start the backend server:
     ```bash
     cd backend
     uvicorn main:app --reload
     ```
   - Start the frontend application:
     ```bash
     cd frontend
     pnpm start
     ```

For more information, please visit repo for each submodule. 
