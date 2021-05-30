# Take debian os as base for the container image
FROM debian:9.5-slim

# copy the local script to the container path
ADD entrypoint.sh /entrypoint.sh

# Give execution permission to the script in the path
RUN chmod +x /entrypoint.sh

# Define the entrypoint of the container, which would execute the container when it starts
ENTRYPOINT ["/entrypoint.sh"]