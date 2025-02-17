.PHONY: install

install: 
	@echo "Installing dependencies..."
	poetry install --no-root

activate:
	@echo "Activating virtual environment..."
	poetry shell

run-pipeline:
	@echo "Running DVC..."
	dvc repro

