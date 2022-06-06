# k8-notes-rdp

### Start a container, and make it run indefinitely
`docker run -d -t -i --name='cantstop-wontstop' kong:latest sh -c "while true; do sleep 2000; done"`

*This is the important part:* `sh -c "while true; do sleep 2000; done"`
