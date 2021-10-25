FROM image-registry.openshift-image-registry.svc:5000/openshift/nginx

COPY . /opt/app-root/src

EXPOSE 8080
CMD ["sh","-c","nginx -g 'daemon off;'"]