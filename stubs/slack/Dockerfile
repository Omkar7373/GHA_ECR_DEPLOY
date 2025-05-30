#FROM ghcr.io/astral-sh/uv:0.5.28
FROM python:alpine
WORKDIR /app
COPY src/ ./src/

ENV PYTHONUNBUFFERED=1
ENV PYTHONPATH=/app:/app/src
CMD ["python ./src/mcp_slack/server.py"]