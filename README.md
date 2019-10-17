# aws-iot-python
Utilities using the Python AWS SDK https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/index.html

Used for creating the AWS
online MQTT lab at https://mqttlab.iotsim.io/aws, and
large-scale prototypes with MIMIC MQTT Simulator https://www.gambitcomm.com/site/mqttsimulator.php

    % python list_things.py
    Usage: listthings.py
  	-a|--access access-key  AWS_ACCESS_KEY_ID
  	-s|--secret secret-key  AWS_SECRET_ACCESS_KEY
  	[-v|--verbose]          verbose output

    % python list_things.py -a 'XXXXX' -s 'XXXX'
    {u'things': [{u'thingArn': u'arn:aws:iot:us-east-1:409128494776:thing/mimic-10', u'version': 1,
    u'thingName': u'mimic-10', u'attributes': {}}, {u'thingArn': u'arn:aws:iot:us-east-1:409128494776:thing/mimic-9',
    u'version': 1, u'thingName': u'mimic-9', u'attributes': {}},...

