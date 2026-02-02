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


# adding procedures


# usage

1. power on - device shows "text dial ready"
2. rotate encoder - scroll through procedures
3. press encoder - preview procedure payload
4. press switch - enter confirmation mode 
5. hold switch 800ms - start injection
6. doule press switch - abort