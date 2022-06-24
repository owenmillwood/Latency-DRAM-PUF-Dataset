# Latency-DRAM-PUF-Dataset

DRAM-Latency-PUF raw response and Grayscale image data from Commodity-Off-The-Shelf (COTS) DDR3 DRAM DIMMs under various environmental conditions.

Each measurement is categorised by the following:

- DIMM Name
  - Location on DIMM (a, b, c, d, e, f, g, h)
    - Temperature (20C, 30C, 40C, 50C)
      - Voltage (1.3v, 1.5v)
        - Challenge Pattern  (0x00, 0x55, 0xFF)
          - Measurement number (1 -> 10)

_latency_dataset.csv_ contains each individual response measurement as a row in the table, including the raw hex output from the memory controller.

_grayscale_images_ contains each measurement represented as a 200x220 grayscale image for use training computer vision models.
