FROM almalinux:9
#CMD ["ping","-c5","google.com"]
#it pings google 5 times
#ENTRYPOINT [ "ping", "-c5", "google.com" ]
#CMD can be overriden but ENTRTYPOINT instructions can't be overriden.. you can mix CMD and ENTRYPOINT for better results...
#CMD is used to supply default args to ENTRYPOINT and we can always override default args from runtime
CMD ["google.com"]
ENTRYPOINT [ "ping", "-c5" ]