
# google.generativeai.protos.GenerateContentResponse.UsageMetadata

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api nocontent">
<td>
  <a target="_blank" href="https://github.com/googleapis/google-cloud-python/tree/main/packages/google-ai-generativelanguage/google/ai/generativelanguage_v1beta/types/generative_service.py#L557-L591">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td>
</table>



Metadata on the generation request's token usage.

<!-- Placeholder for "Used in" -->




<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2"><h2 class="add-link">Attributes</h2></th></tr>

<tr>
<td>

`prompt_token_count`<a id="prompt_token_count"></a>

</td>
<td>

`int`

Number of tokens in the prompt. When ``cached_content`` is
set, this is still the total effective prompt size meaning
this includes the number of tokens in the cached content.

</td>
</tr><tr>
<td>

`cached_content_token_count`<a id="cached_content_token_count"></a>

</td>
<td>

`int`

Number of tokens in the cached part of the
prompt (the cached content)

</td>
</tr><tr>
<td>

`candidates_token_count`<a id="candidates_token_count"></a>

</td>
<td>

`int`

Total number of tokens across all the
generated response candidates.

</td>
</tr><tr>
<td>

`total_token_count`<a id="total_token_count"></a>

</td>
<td>

`int`

Total token count for the generation request
(prompt + response candidates).

</td>
</tr>
</table>



