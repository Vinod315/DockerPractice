# dockerfiles/ADD/Dockerfile
FROM almalinux:9
ADD https://raw.githubusercontent.com/daws-90s/notes/refs/heads/main/session-01.txt /tmp/
ADD sample-1.tar /tmp/                # auto-extracted into /tmp
CMD ["sleep", "100"]

#It can fetch content directly from a URL
#It can automatically extract a tar archive into the destination