# Changelog

## 1.2.2

  - Allow ar_after_transaction 1.x, which supports Active Record 8.1. The 1.x line only moves the ActiveRecord::Base extension into an `ActiveSupport.on_load(:active_record)` hook; the transaction callback code is unchanged.

## 1.2.0

  - When async is false we want to fall back to the original logic (#11 thanks @erf530)
  - ar_after_transaction got updated for 7.1 Rails support (#10 thanks @caelanpthomas and @jeanpauldejong)
  - Introduced a ton of standardization with rubocop

## 1.1.0

I forgot to put any details here

## 1.0.1

I have no idea, I'll find out

## 1.0.0

  - Initial release
