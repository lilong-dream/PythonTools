# this tool splits inFile to outFiles each with certain lines
print('Welcome to use TextSplitter!\n')
inFileName = raw_input('Please input inFileName (include suffix)\n')
outFileName = raw_input('Please input outFileName (without suffix)\n')
lines = raw_input('Please input lines of each file\n')
fp = open(inFileName)
cnt = 1;
fp2 = open(outFileName + str(cnt) + ".txt", "w")
for i, line in enumerate(fp):
    if i == int(lines) * cnt:
        fp2.close()
        cnt += 1
        fp2 = open(outFileName + str(cnt) + ".txt", "w")
    
    fp2.write(line)

fp.close()
fp2.close()
