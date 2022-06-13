# ALchemy-Working-Edition
Last version of Creative ALchemy that works on any sound device

Recently I bought PCI-E soundcard from Creative and was surprised that native ALchemy driver not working. After digging driver binaries in disassembler I found table with supported soundcards, i.e. artifical limitation. So I applied patch to this files similar to last working version from Daniel_K. All this patch does is cancelling hardcoded list of cards and kga-file checking. As a result it will work at all sound cards, not only at Creative.
