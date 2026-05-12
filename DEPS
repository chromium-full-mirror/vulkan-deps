# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '972068c206742412ea26978ae410ec001dfb0620',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e1f872619095e51d3f310be320e77347de1158d4',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '98c842bd561ac67c5ff98d599c8c960ba9edb7fd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '0bb521870594a00a7079381e119da2b4e1a2f859',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '8cfaaa1d4deedc865e52a42e654c5ec0d7d75eb0',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1fbd783a81135634796dd7d89b466d4c252aa883',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '225242ea4847b36e4642064cc4b1b041ed11c2de',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'ca09359985d967d1a6c81d11c2aa28d6ada89cf6',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5a1345c1607c40d15d1f7bcae3b336d984ae9508',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
