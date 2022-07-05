import os
import sys
import argparse
import os
import sys

def get_args():

    parser=argparse.ArgumentParser(
        description='python new project'
        formatter_class=argparse.ArgumentDefaultsHelpFormatter
    )


    parser.add_argument('positional',
                        metavar='str'
                        help='A positional argument')
   
    parser.add_argument('-a',
                        '--arg',
                        metavar='str',
                        help='A named string argument',
                        metavar='str',
                        default=' ')

    parser.add_argument('i',
                        '--int',
                        help='int',
                        type=int,
                        default=0)

    parser.add_argument('-f',
                        '--file',
                        metavar='FILE',
                        type=argparse.FileType('r')
                        default=None)

    parser.add_argument('-o',
                        '--on',
                        help='A boolean flag',
                        action='store_true')
return parser.parse_args()
