FROM perl:latest

WORKDIR /app

COPY cpanfile .

RUN cpanm -n --with-develop --installdeps .

COPY . .

EXPOSE 3000

CMD ["morbo", "./Jumanda"]
