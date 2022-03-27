<template>
  <div class="screen d-flex justify-content-around">
    <!-- Card 1 -->
    <div class="card">
      <div
        class="card__inner"
        @click="onFlipKhoi"
        :class="{ 'is-flipped': isFlipKhoi }"
      >
        <div class="card__face card__face--front"></div>
        <div class="card__face card__face--back">
          <div class="card__content">
            <div class="card__header">
              <img src="./assets/images/khoi.jpg" alt="" class="pp" />
              <h2>KHÔI ĐÁ</h2>
            </div>
            <div class="card__body">
              <h3>19/07/1999 - Thỏ - Cự Giải</h3>
              <p>Cao ráo, thân thiện, lười biếng</p>
              <p>Ước mơ nhỏ nhoi là có bằng ielts</p>
              <p>
                Thích làm việc với máy tính, đá banh, đọc sách, chơi game, làm
                đồ handmade,...
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Gif love -->
    <div style="margin-top: 300px">
      <button
        style="margin-top: -250px; display: flex"
        type="button"
        class="btn btn-success"
        data-toggle="modal"
        data-target="#exampleModalLong"
        @click="playAudio"
      >
        Anniversary 100 Days
      </button>
      <img
        style="border-radius: 50%; width: 200px; margin-top: 180px"
        src="./assets/images/love_1.gif"
        alt=""
      />
    </div>
    <!-- Card 2 -->
    <div class="card">
      <div
        class="card__inner"
        @click="onFlipSu"
        :class="{ 'is-flipped': isFlipSu }"
      >
        <div class="card__face card__face--front"></div>
        <div class="card__face card__face--back">
          <div class="card__content">
            <div class="card__header">
              <img src="./assets/images/Su.jpg" alt="" class="pp" />
              <h2>BÉ SU</h2>
            </div>
            <div class="card__body">
              <h3>24/12/2004 - Carrot - Ma Kết</h3>
              <p>Xinh xắn, đáng yêu, dễ thương</p>
              <p>Giỏi, thông minh, luôn hướng đến sự hoàn hảo</p>
              <p>
                Hướng nội, thích sự dễ thương, thích đồ handmade, nấu ăn,...
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Modal -->
  <div
    class="modal fade"
    id="exampleModalLong"
    tabindex="-1"
    role="dialog"
    aria-labelledby="exampleModalLongTitle"
    aria-hidden="true"
  >
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLongTitle">
            Anniversary 100 days
          </h5>
          <button
            type="button"
            class="close"
            data-dismiss="modal"
            aria-label="Close"
          >
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          <p>
            - Cám ơn bé vì giờ này còn ở bên anh sau bao nhiêu biến cố, 100 ngày
            không phải là khoảng thời gian dài nhưng anh nghĩ nó đủ để anh hiểu
            được em bé phần nào, biết em bé cần gì,..
          </p>
          <p>
            - Xin lỗi em bé của anh, vì nhiều lần anh đã vấp ngã, anh làm tổn
            thương đến em bé của anh, anh thiệt sự xin lỗi em bé nhiều, mong em
            bé bỏ qua cho anh nhaaa
          </p>
          <p>
            - Anh hổng dám hứa gì đâu anh sợ mình hông làm được lắm, anh chỉ cố
            gắng hết mình, đang yêu và mãi yêu thuiiiii, sẽ không bao giờ lùi
            bước hay dừng lại, sẽ luôn cố gắng vì cả 2 ❤️️
          </p>
          <p>
            - Mà hơi trễ ha đồ dễ thương, tại vì bây giờ anh mới hoàn thiện xong
            á, em bé của anh chắc đang ngủ say xưa gòi, nhưng mà em bé của anh
            lạ lắm nha, anh mong và hi vọng em bé sẽ hông nói xạo anh điều gì
            nha, mà hì hì hình như nãy a có like cái trang của bà Jav j đó không
            nhớ tên nữa mà a unlike gòi nè :3
          </p>
          <p>
            - Chúc em bé của anh Khôi ngủ thiệt là ngon nha, mơ thiệt là đẹp,
            luôn luôn có sức khỏe luôn luôn khỏe mạnh có vậy mới làm phiền anh
            Khôi được, chứa a Khôi khỏe lắm à nhen, a Khôi xin được gửi những
            điều tốt đẹp, những điều may mắn nhất giành tới em bé của anh, một
            người rất đặc biệt, rất quan trọng và anh yêu em bé của anh nhiều
            lắm ❤️
          </p>
          <p>
            - Người gì đâu mà dễ thương quá chài, nhưng mà em bé ơi, anh bik bé
            tốt bụng với anh lắm nhưng mà hạn chế mua đồ cho a nhaaaaa kkkkk chứ
            a cũng ngại lắm chớ bộ, nhưng mà mấy đồ bé lựa đồ nào cũng đẹp hết
            trơn,... người gì đâu vùa giỏi vửa thông minh lại còn xinh đẹp, anh
            Khôi làm gì để giữ em bé bên cạnh a Khôi đâyyyy ❤️❤️❤️❤️❤️
          </p>
          <p>
            - Anh Khôi biết anh Khôi còn nhiều thiếu xót lắm, còn thiếu kinh
            nghiệm, còn non nhiều lắm, ... nhưng mà em bé đừng vội bỏ cuộc nha,
            anh Khôi nghĩ a Khôi còn làm được nhiều điều, còn nhiều điều thú vị
            lắm à nhennnnn, hi vọng 2 tháng sauuuu a sẽ sơm gặp em bé ......
          </p>
          <p>
            - úi úi nhưng mà a xin lỗi vì nay a hư a hông nghe lời a ngủ trễ
            nha, không trễ là không có cái zui zui này đâu, anh thấy zui nên a
            gởi cho em bé đó nhaa, mặc dù nó hổng xịn xò j hết trơn, nó chỉ mang
            í nghĩa tinh thần thui ạ, nhưng mà a mong em bé sẽ đón nhận .....
            nha đồ dễ thương hì hì
          </p>
          <p>
            - Điều gì cần nói a cũng nói hết gòi, nói chung giành mọi điều tốt
            đẹp đến giành cho em bé, à mà đúng gòi em bé ơi, còn một điều là a
            mong em bé sẽ chia sẻ stress hay áp lực của cuộc sống cho a nghe
            nha, hông có được giấu trong lòng, dễ bị tổn thương lắm chòi oii, và
            a Khôi cũng cảm thấy a Khôi vô dụng lắm, mặc dù a Khôi trí nhớ hơi
            tệ xíu, nhưng a Khôi sẽ cố gắng cải thiện (note, ghi giấy, ...) sẽ
            tập trung lắng nghe hơn.... chúc em bé của anh Khôi ngủ thiệt ngon
            nha kkkk
          </p>
          <p>
            - Bây h thì a Khôi xin phép đi ngủ nhaaaa, cơ mà nhạc nghe dễ thương
            haaaaa, mà sáng mai nếu em bé đọc được này mà thấy a K chưa dậy thì
            thông cảm giúp a K nhaaa kkk nay hơi đuối nhưng mà nghĩ tới em bé a
            lại có động lực có thêm sức mạnh kkkk, mà xin tấm hình hông cho nha
            tui gym kkk mốt kí đầuuuuuu
          </p>
          <p>
            Anh yêu em bé, cô công chúa của anh nhiều ạ ❤️❤️❤️❤️❤️ nói chung mọi
            thứ của anh là của em hết đó ạ :3 :3 cám ơn đồ dễ thương nhiều nha
          </p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-dismiss="modal">
            Close
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import sound from "./assets/audio/hbd.mp3";
export default {
  name: "App",
  components: {},
  data() {
    return {
      isFlipKhoi: false,
      isFlipSu: false,
    };
  },
  methods: {
    onFlipKhoi() {
      this.isFlipKhoi = !this.isFlipKhoi;
    },
    onFlipSu() {
      this.isFlipSu = !this.isFlipSu;
    },
    playAudio() {
      setTimeout(() => {
        const audio = new Audio(sound);
        audio.loop = true;
        if (typeof audio.loop == "boolean") {
          audio.loop = true;
        } else {
          audio.addEventListener(
            "ended",
            function () {
              this.currentTime = 0;
              this.play();
            },
            false
          );
        }
        audio.play();
        console.log("true");
      }, 2000);
    },
  },
};
</script>
<style scoped>
.screen {
  background-image: url("./assets/images/love.jpg");
  background-attachment: fixed;
}
</style>

