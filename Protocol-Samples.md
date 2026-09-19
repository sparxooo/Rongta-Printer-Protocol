# Protocol / Data packets

I attempted to capture packets from the device using Androids bluetooth snoop log feature but don't think that's fully working. I did capture one or two packets:

Appears to be sent at initial connection

{
    "0": 163,
    "1": 30,
    "2": 28,
    "3": 0,
    "4": 9,
    "5": 0,
    "6": 17,
    "7": 1,
    "8": 25,
    "9": 4,
    "10": 0,
    "11": 111,
    "12": 13,
    "13": 170,
    "14": 106,
    "15": 148,
    "16": 13,
    "17": 241,
    "18": 82
}

Appears to be received possibly as a reply to the previous packet

{
    "0": 163,
    "1": 30,
    "2": 28,
    "3": 0,
    "4": 5,
    "5": 0,
    "6": 33,
    "7": 1,
    "8": 25,
    "9": 0,
    "10": 0,
    "11": 127,
    "12": 164,
    "13": 33,
    "14": 40
}
