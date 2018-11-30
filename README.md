# raw_storage_perf

commands used to execute tests with fio:

random read test:
fio --runtime=60 --rw=randread random-alldevs.fiojob

random write test:
fio --runtime=60 --rw=randwrite random-alldevs.fiojob

sequential write test:
fio --rw=write sequential-alldevs.fiojob

sequential read test
fio --rw=read sequential-alldevs.fiojob
