# Squid Benchmarking

This project benchmarks a Squid proxy server to evaluate its performance under different conditions.
## Project Overview
The goal is to evaluate the performance of the Squid proxy server using different banchmarking tools and methods.This test results provide insights into how Squid handles various types of requests and its overall performance under load.
## How to Run
To run the  benchmarking test,follow these steps:

1.**Set up Squid Proxy**:Ensure that Squid is installed and configured on your system.
2.**Install Apache Benchmark Tool**:You can install it using the following command:
```bash
sudo apt install apache2-utils
3.Run the Benchmark:Run the Apache Benchmark tool to simulate web request,replacing example.com with your desired URL:
ab -n 1000 -c 10 http://yourwebsite.com/
4.Monitor Squid Logs:To monitor Squid's log in real-time:
sudo tail -f /var/log/squid/access.log
Results
The results of the benchmark test are stored in the benchmark_results.txt file,which includes details about the number of requests,response times,and other relevant metrics.
