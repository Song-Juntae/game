# minecraft

    def get_infinite_mineshaft_seed(n):
        return int(bin(n*4)+'111011101001010100010100101110',2)

    def repeat_world(n):
        return int(bin(n*2)+'1100011011111111100111100100100',2)