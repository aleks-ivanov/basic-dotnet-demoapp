FROM mcr.microsoft.com/vscode/devcontainers/dotnet:0.201.7-5.0

# Install NuGet CLI
RUN sudo apt-get update -y && \
	sudo apt-get install -y nuget && \
	# Install gcc, g++ and make
	sudo apt update && \
	sudo apt install build-essential -y