# ion_chromium_b
/dev/ion enabled chromiumos builds (kukui, amd64)
Note: Despite having built these (and many other) chromeos images in the last 24 hours, I have not been able to boot a single one up for testing.
Ideally: 	boot the kukui image on compatible hardware, verify /dev/ion exists
Less ideally:	Boot the amd64 image on compatible hardware, verify /dev/ion exists, and assume the same is true for kukui

After spending > 12 hours trying to accomplish this on variety of platforms and emulators, 
I realized i could buy an MT8183 based device on amazon for $250. It arrives Thurs the 22nd.

f5ce1eb92a40c7df305491a75b1bd4b7  amd64generic-R92_2021_04_20-chromiumos_dev_image.zip
3709ffa671982b451074afd6e7afa558  amd64generic-R92_2021_04_20-chromiumos_test_image.zip
d4496be31fe9e0f06c00431729a69397  kukui-R92_2021_04_20-chromiumos_dev_image.zip
934410e489bafc9fef6f8fb3a076a917  kukui-R92_2021_04_20-chromiumos_test_image.zip
