FROM ansibleplaybookbundle/apb-base
# MAINTAINER {{ $MAINTAINER }}

LABEL "com.redhat.apb.version"="0.1.0"
LABEL "com.redhat.apb.spec"=\
"aWQ6IDZmMTgwY2I0LTMwZDQtNGE4YS05NzVlLWU5MWNhN2VkMmVkOQpuYW1lOiBldGhlcnBhZC1h\
cGIKaW1hZ2U6IGFuc2libGVwbGF5Ym9va2J1bmRsZS9ldGhlcnBhZC1hcGIKZGVzY3JpcHRpb246\
IE5vdGUgdGFraW5nIHdlYiBhcHBsaWNhdGlvbgpiaW5kYWJsZTogVHJ1ZQphc3luYzogb3B0aW9u\
YWwKbWV0YWRhdGE6IAogIGRvY3VtZW50YXRpb25Vcmw6IGh0dHBzOi8vZ2l0aHViLmNvbS9ldGhl\
ci9ldGhlcnBhZC1saXRlL3dpa2kKICBpbWFnZVVybDogaHR0cHM6Ly90cmFuc2xhdGV3aWtpLm5l\
dC9pbWFnZXMvdGh1bWIvNi82Zi9FdGhlcnBhZF9saXRlLnN2Zy8yMDBweC1FdGhlcnBhZF9saXRl\
LnN2Zy5wbmcKICBkZXBlbmRlbmNpZXM6IFsnZG9ja2VyLmlvL21hcmlhZGI6bGF0ZXN0JywgJ2Rv\
Y2tlci5pby90dmVsb2NpdHkvZXRoZXJwYWQtbGl0ZTpsYXRlc3QnXQogIGRpc3BsYXlOYW1lOiBF\
dGhlcnBhZCAoQVBCKQogIGxvbmdEZXNjcmlwdGlvbjogQW4gYXBiIHRoYXQgZGVwbG95cyBFdGhl\
cnBhZCBMaXRlCnBsYW5zOgogIC0gbmFtZTogZGVmYXVsdAogICAgZGVzY3JpcHRpb246IEEgc2lu\
Z2xlIGV0aGVycGFkIGFwcGxpY2F0aW9uIHdpdGggbm8gREIKICAgIGZyZWU6IHRydWUKICAgIG1l\
dGFkYXRhOgogICAgICBkaXNwbGF5TmFtZTogRGVmYXVsdAogICAgICBsb25nRGVzY3JpcHRpb246\
IFRoaXMgcGxhbiBwcm92aWRlcyBhIHNpbmdsZSBFdGhlcnBhZCBhcHBsaWNhdGlvbiB3aXRoIG5v\
IGRhdGFiYXNlCiAgICAgIGNvc3Q6ICQwLjAwCiAgICBwYXJhbWV0ZXJzOgogICAgICAtIG5hbWU6\
IG1hcmlhZGJfbmFtZQogICAgICAgIHJlcXVpcmVkOiB0cnVlCiAgICAgICAgZGVmYXVsdDogZXRo\
ZXJwYWQKICAgICAgICB0eXBlOiBzdHJpbmcKICAgICAgICB0aXRsZTogTWFyaWFEQiBEYXRhYmFz\
ZSBOYW1lCiAgICAgIC0gbmFtZTogbWFyaWFkYl91c2VyCiAgICAgICAgcmVxdWlyZWQ6IHRydWUK\
ICAgICAgICBkZWZhdWx0OiBldGhlcnBhZAogICAgICAgIHRpdGxlOiBNYXJpYURCIFVzZXIKICAg\
ICAgICB0eXBlOiBzdHJpbmcKICAgICAgICBtYXhsZW5ndGg6IDYzCiAgICAgIC0gbmFtZTogbWFy\
aWFkYl9wYXNzd29yZAogICAgICAgIGRlZmF1bHQ6IGFkbWluCiAgICAgICAgdHlwZTogc3RyaW5n\
CiAgICAgICAgZGVzY3JpcHRpb246IEEgcmFuZG9tIGFscGhhbnVtZXJpYyBzdHJpbmcgaWYgbGVm\
dCBibGFuawogICAgICAgIHRpdGxlOiBNYXJpYURCIFBhc3N3b3JkCiAgICAgIC0gbmFtZTogbWFy\
aWFkYl9yb290X3Bhc3N3b3JkCiAgICAgICAgZGVmYXVsdDogYWRtaW4KICAgICAgICB0eXBlOiBz\
dHJpbmcKICAgICAgICBkZXNjcmlwdGlvbjogcm9vdCBwYXNzd29yZCBmb3IgbWFyaWFkYgogICAg\
ICAgIHRpdGxlOiBSb290IFBhc3N3b3JkCg=="

ADD playbooks /opt/apb/actions
ADD roles /opt/ansible/roles
RUN chmod -R g=u /opt/{ansible,apb}

USER apb
