FROM public.ecr.aws/bitnami/nginx:1.21

COPY . /app

EXPOSE 8080
CMD ["sh","-c","nginx -g 'daemon off;'"]