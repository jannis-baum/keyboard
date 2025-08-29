SRC=$(shell find src -type f -name '*.ts')
DEST=$(HOME)/.config/karabiner/karabiner.json

.PHONY: build
build: $(DEST)

$(DEST): $(SRC) package.json yarn.lock
	yarn && yarn build
