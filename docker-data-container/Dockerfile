FROM python

SHELL ["/bin/bash", "-c"]

ENV INPUT_DIR=/input
ENV OUTPUT_DIR=/output

COPY . .

RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir -r requirements.txt

CMD bash -c "python ./py_script.py; exec bash"
