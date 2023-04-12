FROM nvcr.io/nvidia/pytorch:23.03-py3

COPY requirements.txt /tmp/pip-tmp/
RUN pip install --no-cache-dir -r /tmp/pip-tmp/requirements.txt && \
  rm -rf /tmp/pip-tmp
