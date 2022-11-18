// Build

docker image build -t christmastree .

// Run

docker run -p 9988:8000 -p 9987:80 christmastree:latest
