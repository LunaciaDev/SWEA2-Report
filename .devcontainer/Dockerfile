FROM quay.io/fedora/fedora-minimal:latest

RUN echo install_weak_deps=False >> /etc/dnf/dnf.conf
RUN dnf install -y git eza texlive-scheme-basic latexmk 'tex(ngerman.ldf)' 'tex(acronym.sty)' 'tex(listingsutf8.sty)' 'tex(textpos.sty)' 'tex(blindtext.sty)' 'tex(harveyballs.sty)' 'tex(chngcntr.sty)'