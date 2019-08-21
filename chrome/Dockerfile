FROM yukinying/chrome-headless-browser:65.0.3322.3

EXPOSE 9222

COPY entrypoint.sh .

RUN chmod +x ./entrypoint.sh

ENTRYPOINT ["/usr/local/bin/tini", "--", "./entrypoint.sh"]