If you configure SAML SSO, members of your {% data variables.product.prodname_dotcom %} organization will continue to log into their user accounts on {% data variables.product.prodname_dotcom %}. 当成员访问组织内使用 SAML SSO 的资源时，{% data variables.product.prodname_dotcom %} 会将该成员重定向到 IdP 进行身份验证。 身份验证成功后，IdP 将该成员重定向回 {% data variables.product.prodname_dotcom %}，然后成员可以访问组织的资源。