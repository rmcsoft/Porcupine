alsademo: main.cpp
	$(CXX) -Ofast main.cpp -o alsademo \
	-L$(STAGING_DIR)/usr/lib -I$(STAGING_DIR)/usr/include -lasound \
	-I../../include -L../../lib/raspberry-pi/arm11 -Wl,-rpath ../../lib/raspberry-pi/arm11 -lpv_porcupine
