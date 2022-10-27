# Let's Play with MQTT

## Getting Started

<https://killercoda.com/playgrounds/scenario/ubuntu>

```text
sudo apt-get install mosquitto -y
```

```text
sudo apt-get install mosquitto mosquitto-clients -y
```

```text
mosquitto_sub -t "test_topic"
```

```text
mosquitto_pub -t "test_topic" -m "Hello World!"
```

## References

<http://www.steves-internet-guide.com/mqtt-works/>

<https://learn.sparkfun.com/tutorials/introduction-to-mqtt>

<https://mqtt-explorer.com/>
