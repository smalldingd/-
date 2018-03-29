# -def chengfa():
    row = 1
    while row <= 9:  # 控制行数

        col = 1
        while col <= row:  # 控制列数
            print("%d * %d = %d" % (col, row, (col * row)), end="\t")
            col += 1

        print()
        row += 1
