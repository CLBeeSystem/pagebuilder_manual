---
description: 조건부 태그 변경 액션으로 더 복잡한 액션을 만들 수 있습니다.
---

# 조건부 태그 변경 액션 소개

## ① 조건부 태그 변경 액션 <a id="1"></a>

태그값 비교 조건부 액션을 만들어 놓고, 다른 액션의 타켓을 태그값 변경 액션을 이용하시면 더욱 다양한 조건부 액션을 활용할 수 있습니다. 태그값 변경 액션으로 기존에 설정한 태그에 태그를 더 추가하거나, 삭제, 변경을 할 수 있습니다.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-LsumUn8IPNwhR6_7D2l%2F-LsumZhaANZMQ-hKgoEt%2Fimage.png?alt=media&token=3782fa8b-d709-475f-84f9-2c93d4f1b54b)

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#xD0DC;&#xADF8;&#xAC12; &#xBCC0;&#xACBD;</th>
      <th style="text-align:left">&#xC124;&#xBA85;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&#xCD94;&#xAC00;</td>
      <td style="text-align:left">&#xD604;&#xC7AC; &#xD0C0;&#xCF13;&#xC758; &#xD0DC;&#xADF8;&#xC5D0; &#xB2E4;&#xB978;
        &#xD0C0;&#xCF13;&#xC758; &#xD0DC;&#xADF8;&#xAC00; &#xCD94;&#xAC00; &#xB429;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:left">&#xAD50;&#xCCB4;</td>
      <td style="text-align:left">&#xD604;&#xC7AC; &#xD0C0;&#xCF13;&#xC758; &#xD0DC;&#xADF8;&#xAC00; &#xB2E4;&#xB978;
        &#xD0C0;&#xCF13;&#xC758; &#xD0DC;&#xADF8;&#xB85C; &#xAD50;&#xCCB4; &#xB429;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:left">&#xC0AD;&#xC81C;</td>
      <td style="text-align:left">&#xD604;&#xC7AC; &#xD0C0;&#xCF13;&#xC758; &#xD0DC;&#xADF8;&#xC5D0;&#xC11C;
        &#xB2E4;&#xB978; &#xD0C0;&#xCF13;&#xC774; &#xD0DC;&#xADF8;&#xAC00; &#xAC19;&#xC744;
        &#xACBD;&#xC6B0;&#xC5D0;&#xB9CC; &#xD0DC;&#xADF8;&#xAC00; &#xC0AD;&#xC81C;&#xB429;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:left">&#xC804;&#xCCB4;&#xC0AD;&#xC81C;</td>
      <td style="text-align:left">&#xD0C0;&#xCF13;&#xC758; &#xAE30;&#xC874; &#xD0DC;&#xADF8;&#xAC12;&#xC744;
        &#xD3EC;&#xD568;&#xD558;&#xC5EC; &#xBAA8;&#xB4E0; &#xD0DC;&#xADF8;&#xAC00;
        &#xC0AD;&#xC81C;&#xB429;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:left">*&#xC0AC;&#xC6A9;&#xC790;&#xC785;&#xB825;</td>
      <td style="text-align:left">
        <p>(&#xC704;&#xC758; &#xD0DC;&#xADF8;&#xAC12; &#xBCC0;&#xACBD; &#xD0C0;&#xC785;
          &#xC120;&#xD0DD; &#xD6C4; &#xB098;&#xD0C0;&#xB0A8;)</p>
        <p>&#xC0AC;&#xC6A9;&#xC790;&#xAC00; &#xC785;&#xB825;&#xD55C; &#xD0DC;&#xADF8;&#xB85C;
          &#xD604;&#xC7AC; &#xD0C0;&#xCF13;&#xC758; &#xD0DC;&#xADF8;&#xAC00; &#xBCC0;&#xACBD;&#xB429;&#xB2C8;&#xB2E4;</p>
      </td>
    </tr>
  </tbody>
</table>## ② 태그값 변경 액션 넣는 방법 <a id="2"></a>

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-Lszh-A5o_FA2WPUS2RK%2F-Lszln2PxUBeoK2CHHWo%2F%EC%A1%B0%EA%B1%B4%EB%B6%80%EC%95%A1%EC%85%981-7.png?alt=media&token=399df648-18ac-40ef-9b26-bcc422ad274f)

\(1\) 태그 비교 조건부 액션을 만듭니다.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-Lszh-A5o_FA2WPUS2RK%2F-LszlpYB6nEkki9TxFKK%2F%EC%A1%B0%EA%B1%B4%EB%B6%80%EC%95%A1%EC%85%981-8.png?alt=media&token=86e7994b-7832-4783-9892-8241190fdae3)

\(2\) 태그값 변경 액션을 실행시킬 객체를 선택한 뒤 트리거를 선택합니다.

\(3\) 타켓이 상관없이 액션을 만든 뒤 타임라인에 생성된 액션을 선택합니다.

\(4\) 타켓을 ‘태그값 변경\(추가, 삭제, 교체, 모두 제거\) ’으로 선택합니다.

\(5\) 태그값 변경이 될 다른 타켓을 선택한 뒤 액션 모드를 종료합니다.

​

