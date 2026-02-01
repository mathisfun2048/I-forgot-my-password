hello world!!!

# To build for hardware

'''

export PICO_SDK_PATH=/path/to/pico-sdk

mkdir build && cd build

cmake .. && make -j4


'''



# to run tests

cd build-tests
./test_runner

