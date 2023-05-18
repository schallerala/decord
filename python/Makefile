clean:
	-rm -rf build decord.egg-info dist

build-wheel:
	@# https://wheel.readthedocs.io/en/latest/quickstart.html#quickstart
	poetry run python -m pip install build
	poetry run python -m build --wheel