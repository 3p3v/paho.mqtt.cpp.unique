# Eclipse Paho MQTT C++ Client Library - unique_ptr callbacks

Fork of [Eclipse Paho MQTT C++ Client Library](https://github.com/eclipse/paho.mqtt.cpp).
Original library uses raw pointers for passing callbacks while publishing. 
In fork it was changed to smart pointers (unique_ptrs) so the lifetime of these objects is managed by the library, not by a user.