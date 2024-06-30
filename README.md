# Kyber.PAKE
all: \
	test_kyber512 \
	test_kyber768 \
	test_kyber1024 \
	test_speed512 \
	test_speed768 \
	test_speed1024 \

pake_kyber512: \
  test_kyber512 \

pake_kyber768: \
  test_kyber768 \

pake_kyber1024: \
  test_kyber1024 \

speed_kyber512: \
  test_speed512 \

speed_kyber768: \
  test_speed768 \

speed_kyber1024: \
  test_speed1024 \  


## Acknowledgment

- This research was partially supported by TUBITAK under Grant No. 121R006

  
