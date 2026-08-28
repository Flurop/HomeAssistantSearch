FROM ghcr.io/home-assistant/base:latest

RUN apk add --no-cache python3

WORKDIR /HomeAssistantSearch

CMD ["python3", "-m", "http.server", "8000"]