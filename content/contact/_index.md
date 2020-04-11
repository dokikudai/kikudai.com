---
title: "Contact"
linkTitle: "お問い合わせ"
---
<section id="contact">
    <div class="container">
        <div class="row">
            <div class="col-lg-12 text-center">
                <h2>お問い合わせ</h2>
                <hr class="star-primary">
            </div>
        </div>
        <div class="row">
            <div class="col-lg-8 col-lg-offset-2">
                <form action="//formspree.io/contact@kikudai.com" method="POST" name="sentMessage" id="contactForm" novalidate="">
                    <div class="row control-group">
                        <div class="form-group col-xs-12 floating-label-form-group controls">
                            <label>お名前</label>
                            <input type="text" name="name" class="form-control" placeholder="お名前" id="name" required="" data-validation-required-message="Please enter your name." data-ol-has-click-handler="">
                            <p class="help-block text-danger"></p>
                        </div>
                    </div>
                    <div class="row control-group">
                        <div class="form-group col-xs-12 floating-label-form-group controls">
                            <label>メールアドレス</label>
                            <input type="email" name="_replyto" class="form-control" placeholder="メールアドレス" id="email" required="" data-validation-required-message="Please enter your email address." data-ol-has-click-handler="">
                            <p class="help-block text-danger"></p>
                        </div>
                    </div>
                    <div class="row control-group">
                        <div class="form-group col-xs-12 floating-label-form-group controls">
                            <label>TEL</label>
                            <input type="tel" name="tel" class="form-control" placeholder="TEL" id="phone" required="" data-validation-required-message="Please enter your phone number." data-ol-has-click-handler="">
                            <p class="help-block text-danger"></p>
                        </div>
                    </div>
                    <div>
                        <input type="hidden" name="_subject" value="お問い合わせ" data-ol-has-click-handler="">
                        <input type="text" name="_gotcha" style="display:none" data-ol-has-click-handler="">
                    </div>
                    <div class="row control-group">
                        <div class="form-group col-xs-12 floating-label-form-group controls">
                            <label>お問い合わせ内容</label>
                            <textarea rows="5" name="message" class="form-control" placeholder="お問い合わせ内容" id="message" required="" data-validation-required-message="Please enter a message." data-ol-has-click-handler=""></textarea>
                            <p class="help-block text-danger"></p>
                        </div>
                    </div>
                    <div class="purpose-of-use">
                        <p>※入力していただいた個人情報は、お問い合わせ以外の目的で使用いたしません。 </p>
                    </div>
                    <br>
                    <div id="success"></div>
                    <div class="row">
                        <div class="form-group col-xs-12">
                            <button type="submit" class="btn btn-success btn-lg">送信</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </div>
</section>
