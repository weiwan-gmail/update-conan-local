# update_conan_local
Update conan local cache



# Prerequiste

`pip install wheel`
`pip install setuptool`
`pip install twine`

# Build and Upload
`python setup.py sdist bdist_wheel`
`twine upload dist/*`


# Usage
`pip install update-conan-local`


`from update_conan_local.main import find_cache`
`find_cache(conanfile_dir)`