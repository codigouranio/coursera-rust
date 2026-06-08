.PHONY: format lint test build clean check dev all update

# Format code
format:
	cargo fmt

# Lint with Clippy
lint:
	cargo clippy --all-targets --all-features -- -D warnings

# Run tests
test:
	cargo test

# Build release version
build:
	cargo build --release

# Quick compile check
check:
	cargo check

# Run the program
dev:
	cargo run

# Full check (recommended before commit)
all: format lint test build

# Update dependencies
update:
	cargo update

# Clean build artifacts
clean:
	cargo clean
