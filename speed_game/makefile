CC	= arm-linux-gcc            # 컴파일러 이름
CFLAGS	= -O2                  # 컴파일러 옵션
LDFLAGS = -lpthread            # 참조 라이브러리

all : speed_game    # 타겟 정의(내가 만들고자 하는 파일명)

speed_game : *.c *.h
	$(CC) $(CFLAGS) -o $@ $^ $(LDFLAGS)
# $@는 타겟(파일명), $^는 의존성(소스)
clean :
	@rm -rf *.o speed_game